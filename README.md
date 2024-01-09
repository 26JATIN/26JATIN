# This Shell script allows you to extract text using screenshot in any linux desktop enviornment

## Here are few steps for different distribution to follow before using this script

### For Fedora based distribution

```
sudo dnf install gnome-screenshot.sh
sudo dnf install xclip
sudo dnf install tesseract-ocr
sudo dnf install tesseract-ocr-eng
```


### For Ubuntu based distribution

```
sudo add-apt-repository ppa:alex-p/tesseract-ocr5
sudo apt-get install tesseract-ocr
sudo apt-get install tesseract-ocr-eng
sudo apt-get install gnome-screenshot
sudo apt-get install xclip
```

### For Arch based distribution
```
sudo pacman -S gnome-screenshot
sudo pacman -S xclip
sudo pacman -S tesseract-ocr
sudo pacman -s tesseract-ocr-eng
```


# important note!
### How to run this bash script?
1.copy Text_Extractor.sh in your home directory. \
2.open terminal and type ./Text-Extractor.sh. \
3.Select area you want to capture text from. \
4.Now assign a shortcut key ctrl+t and assign command ./Take-Screenshot.sh, so that everytime when you press ctrl+t this script executes.
