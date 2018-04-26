# Week 3 SciServer Intro and TensorFlow Tutorial

## Quick-Getting started with SciServer Compute

1. Login to alpha02.sciserver.org with your account and go to Compute
2. Create a new container (Docker container), choose the type to be Python, and a container Jupyter notebook interface will be created.
3. On the right hand side, go to New-> terminal and a black terminal interface will appear.
4. In this order in the terminal, type each of these at a time (separated by a comma) and hit enter:
5. ls, cd home, ls, cd idies, cd workspace, cd storage, cd YOURUSERNAME, cd persistent, ls
6. Clone this repository (or your fork of the repository): `git clone https://github.com/UCLAMLRG/reading_group_2018_spring`
6. the repository will now be in your persistent folder.
7. Navigate to week3 and open the TensorFlow jupyter notebook for the tutorial or create your own new notebook.

**NOTE**: Only data stored in `persistent` will be saved!
From SciServer team: :You should keep all your
important files in your persistent directory, two levels below Storage. The
full path is:

/home/idies/workspace/Storage/{YOUR USERNAME}|/persistent

Files you put in persistent are guaranteed to be preserved across logins.
Packages install into the container rather than the filesystem, so you are OK there. 
That also means you will need to reinstall those packages if you delete
the container, or if you work with the same files in a different container.

If you check the box SDSS in container creation, that just mounted an existing
volume so you can access it. The volume is at the same level as Storage and
Temporary, and is called sdss_das.

Lastly, there is as of yet no way to check your quota usage from within the
Compute site directly, but there is from the new SciServer Dashboard. 


## TensorFlow Tutorial

- Reading: [Ch. 9 Hands-On Machine Learning](http://proquest.safaribooksonline.com/book/programming/9781491962282/9dot-up-and-running-with-tensorflow/tensorflow_chapter_html)
- Notebook from reading: [09_up_and_running_with_tensorflow.ipynb](09_up_and_running_with_tensorflow.ipynb)
- Introduction from Official TensorFlow site [https://www.tensorflow.org/get_started/](https://www.tensorflow.org/get_started/)
