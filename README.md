# YouTube-Downloader

# Foobar

Pytube is a lightweight, Pythonic, dependency-free, library (and command-line utility) for downloading YouTube Videos.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install pytube.

```bash
pip install pytube
```

## Usage

```python
#lmport the library 
from pytube import YouTube 

#ask user to type in the link 
link = input("Enter the link of youtube video: "); 

#creating an object 
yt = YouTube(link) 

#to get the highest resolution 
ys = yt.streams.get_highest_resolution(), 

#show the message until downloading 
print("Downloading..." )

#specifying the location for this video 
ys.download("Downloads\python") 

#show the message when download is completed 
print("Download completed!!")
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
