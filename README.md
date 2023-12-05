# MLcybersec-ECE-GY-9163_Lab4

Th dataset can be found [here](https://drive.google.com/drive/folders/13o2ybRJ1BkGUvfmQEeZqDo1kskyFywab) and original badnet models [here](https://github.com/csaw-hackml/CSAW-HackML-2020/tree/master/lab3/models).

The structure I used on my google drive is as follows.
├── ML for Cybersecurity 
    ├── CSAW-HackML-2020-master
        ├── Lab3
            └── cl
                └── valid.h5 // this is clean validation data used to design the defense
                └── test.h5  // this is clean test data used to evaluate the BadNet
            └── bd
                └── bd_valid.h5 // this is sunglasses poisoned validation data
                └── bd_test.h5  // this is sunglasses poisoned test data
            ├── models
                └── bd_net.h5
                └── bd_weights.h5
        ├── REPAIRED_MODELS
            └── bd_repaired_2_weights.h5
            └── bd_repaired_2.h5
            └── bd_repaired_4_weights.h5
            └── bd_repaired_4.h5
            └── bd_repaired_10_weights.h5
            └── bd_repaired_10.h5