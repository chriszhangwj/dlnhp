# dlnhp
wz4515.zip contains the the baseline and the improved methods for EE3-25 Deep Learning course.

Different optimisers are suggested for different networks, as suggested in the scripts: <br/>
Use Adam(lr=0.0001, beta_1=0.9, beta_2=0.999, epsilon=1e-8, decay=0.0, amsgrad=False) for training all U-Net denoising network. <br/>
Use RMSprop(lr=0.0001, rho=0.9, epsilon=None, decay=0.0) for training descriptor networks with margin and margin hnm losses. <br/>
Use Adam(lr=0.00001, beta_1=0.9, beta_2=0.999, epsilon=1e-8, decay=0.0, amsgrad=False) for training descriptor networks with ratio and ratio hnm losses. <br/>
Use RMSprop(lr=0.001, rho=0.9, epsilon=None, decay=0.0) for training HardNet.<br/>

This repository is subject to updates as further work is carried out on the coursework.
