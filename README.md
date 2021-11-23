# SSH Transfer
Python implementation of SSH file transfer across servers.

## Requirements

*   paramiko=2.7.2

## Usage

* Config Preparation

 Configure some information about the target server, including ip, port, username and password.

 * Usage
  ```
  mkdir_remote(remote_dir) # Create a folder on the target server
  upload_remote(local_dir, remote_dir) # Upload local files to the target server
  download_remote(remote_dir, local_dir) # Download the file from the target server to the local
  ```

 **remote_dir** is the file location of the target server, **local_dir** is the local file location.

