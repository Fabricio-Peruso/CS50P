# Replace_Files
#### Video Demo:  https://youtu.be/4J-aek3OM5k
#### Description:

This project is one code that I make for my personal use. I have a problem with a lot o images/photos from my wife and daugther that was taked from the cellphone. Have some situations that I lost the date that the file was created. In cases like that I put all photos in one directory and I have a dificult to now where the file was created. With this simple code you inform the source( were your media files are) and destination. As the result you will have have all media files with the date in the beginnig of the file name.

#### The Processes:

When you inform one source the program not only see in the current level of the directory, it tries to find other files schearching recursively in the source. That is good for me because I wan't my media files in one centralized folder and if I can see the oldest or the newer I just need to ordered by name. I use the Standard [ Year(YYYY) + Month(MM) + Day(DD) + "_" + File Name ] the helps to do this process

#### Tecnology:

This simple project was developed in Python 3

#### How to run the project

Download the code and run like this:

```bash
python3 project.py -o <path1> -d <path2>
```

Where:

    -o : is the source directory
    -d : is the destiny directory

#### Author

Fabricio Peruso Ferreira
