# DHT
A small Distributed Hash Table designed for a course assignment


USAGE python node.py 8000
-----------------------------------------------------------------------------------------
			                        INSTRUCTIONS FOR TESTING
-----------------------------------------------------------------------------------------
Create folders named between 0 and 8 inclusive, representing the hash value. 
Copy the file node.py to each of the folders and run the file from the folders
For example, in Folder 3, run python node.py 8003

The Folder 1 contains files that can be uploaded and downloaded. Other folders should be empty
The Hashes of the files are:
- file: 10_SDS.pdf 		hash: 0
- file: animated_1.mkv 		hash: 4
- file: video_1.mp4		hash: 3
- file: 226.txt			hash: 7

To check for download resuming, create a new document in folder 7 named 10_SDS.pdf
This will be blank as of now. Now download the file again from the terminal. The
file will now contain data. 
 
