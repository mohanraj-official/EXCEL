# Installing Microsoft Excel (Office Deployment Tool)

## Step 1. Open Browser

* Open Google Chrome.

## Step 2. Download Office Deployment Tool

* Search for Office Deployment Tool.
* Open the first official Microsoft link.
* Download the setup file.

## Step 3. Create Configuration File

* Search for Office Customization Tool.
* Open the first official Microsoft link.

### Product and Release

* Select 64-bit.
* Select required apps.

  * Excel.
  * Word.
  * PowerPoint.

### Language

* Select English (United States).

* Click Next for all remaining options.

* Click Finish.

* Click Export.

* Download the configuration.xml file.

## Step 4. Extract Office Deployment Tool

* Open File Manager.
* Locate the downloaded Office Deployment Tool .exe file.
* Run the file.
* Click Accept.
* Choose a destination folder.
* Complete extraction.

## Step 5. Replace Configuration File

* Open the extracted folder.
* Delete the default sample configuration file.
* Copy and paste the downloaded configuration.xml file into the same folder.

## Step 6. Copy Folder Path

* Open the folder named Office.
* Copy the full folder path from the address bar.

## Step 7. Open Command Prompt

* Open Command Prompt as Administrator.
* Type `cd` and paste the copied folder path.
* Press Enter.

## Step 8. Install Excel 365

* Run the following command:

  ```
  setup /configure configuration.xml
  ```
* Press Enter.
* Wait for installation to complete.

## Step 9. Verify Installation

* Close Command Prompt.
* Open Excel from Start Menu.
* Check whether Excel opens successfully.


* Silent install version.
* Troubleshooting section for errors.
