# python_calculate_and_export_FRF

During multiple **FRF (frequency response function) measurements**, we have one file where all the measurements are stored in one place in data representation as follows: frequency, imaginary part of the signal, real part of the signal.
**If you want to depict the data** in a selective way (not everything needs to be depicted, only selected measurement), you need to have multiple exports representing the measured files.
**Script written in Python takes** a single **file** with multiple measurement datas, **separate them**based on the title/head of the measurement **and recalculate phase and amplitude of the signal**from the original data (from imaginary and real part of the signal).
