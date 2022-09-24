# My scripts

---

My scripts for various purposes..

### work with github

 -  **git-repo**
    -  Creates a repository on a remote server (https://github.com) and a local repository if there was none before. And configures the local repository.
 -  **github**
    -  Also like git-repo, with additional functionality.
    - Supports commands:
      -  'repo' - creates a repository on the https://github.com and a local repository if none exists. Configures the local repository.
      -  'push' - uploads the committees to a remote repository.
   	- Prompts user:
      -  repository name (default is local repository name);
      -  user name on github, default account name (may not be the same as github user name) or reads from user settings file (created manually);
      -  access token on github. Enter by hand or read from a file previously created;
      -  repository description, may be empty (not to be confused with committee description).
    -  You can configure the script from the inside, editing some parameters.

### working with images

 -  **photo-import**
    -  Imports photos to a photo gallery on your computer. As a script startup parameter, you can pass the directory name from where the photos will be imported. The import comes from the specified directory and all nested subdirectories. When importing, you can:
       - change the quality of photos and their size,
       - can be imported unchanged,
       - set file creation date according to EXIF data
       - All settings for the script are made inside the script itself.
 -  **image_menu**
    -  Converts images from one format to another, with conversion settings, through a graphical interface.
    -  Supports conversion to formats:
       -  jpg;
       -  png;
       -  and packing in a multi-end pdf file.
    -  The script was written for use in the context menus of file managers.
 -  **photo_menu**
    -  allows:
       - compress photos;
       - change the size of photos;
       - renames the files to the YYYYMMDD_HHMMSS view.    -  Использует графический интерфейс.
    -  The main application of the script in the context menus of file managers.

### work with pdf files

 -  **pdf_service_menu**
    -  Working with pdf files, through the context menu of file managers.
    -  Uses GUI.
    -  Many features.
 -  **pdfmark**
    -  Combines pdf files into a single document and adds bookmarks to the resulting file. The bookmark name is the name of the files to merge.
	
### programming

 -  **create-bash**
    -  Creates an empty bash creep and sets the executable flag.
 -  **create-py-project**
    - Creates a general purpose project structure.
    - Configures directories, creates and populates some project files.
    - Installs and activates virtual space in the project directory.
    - Activates the VCS and makes a primary commit.
### utils

 -  **script-install**
    -  Installs custom scripts.
 -  **cache-cleaning**
    -  Cache cleaning updated
 -  **shinst**
    -  Copying user scripts and their man pages

### auxiliary

 -  **colors.sh**
    -  Set up text attributes for shell scripts.
 -  **gz**
    -  Unpacking (packing) gz archives.
 -  **whtm**
    -  Download sites. Script-shell for wget.

### other

 -  **random**
    -  Alphanumeric random phrase generator.
