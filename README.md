# Image Downloader
### Takes url of websites, downloads all images in that website and saves metadata about them in an excel sheet

## Set Up (If it s not already set up in your computer)
- install `pipenv`
    ```sh
    pip install pipenv
    ```
- install the required dependencies from the `pipfile`
    ```sh
    pipenv install
    ```

# Run
- Run the following command to scrape the info
    ```sh
    pipenv run python image_downloader.py
    ```


## Tweaks
- Edit the variable `FILE_PATH` to change the path of input excel file
- Name the excel sheet with input urls as `Input`


