# Scale-and-convert-images-using-PIL
Updating images format ,rotate images 90 degree and Resize images
# first download your image folder using given command below in bash shell:
curl -c ./cookie -s -L "https://drive.google.com/uc?export=download&id=$11hg55-dKdHN63yJP20dMLAgPJ5oiTOHF" > /dev/null | curl -Lb ./cookie "https://drive.google.com/uc?export=download&confirm=`awk '/download/ {print $NF}' ./cookie`&id=11hg55-dKdHN63yJP20dMLAgPJ5oiTOHF" -o images.zip && sudo rm -rf cookie
# listing the file in in same root directory
ls
# unzipping the zip file
unzip images.zip 
# listing the unzip images in images directory 
ls ~/images  
# if pillow library is not installed in your machine install it by using command PIL library install in your machine:
pip3 install pillow 
# Write python script for updating images
# grant executable permission to the script file
chmod +x <script.py>
# run the scripted file 
./<script_name>.py
