# SubmittalXpress
Program that will significantly speed up the process of creating product-data submittals in the construction industry.
Starting out, this software focuses only on Division 22: Plumbing with plans to expand to other divisions within the construction industry.

# Program Process:
1. Program will read in a full sized project specification and be able to extrapolate all useful pieces of information necessary for creating product submittals (examples of specifications provided in the immediate first project directory)
2. Program will then prompt user to input the preferred specification sections in which to create a submittal for by method of checkboxes (information found during step 1)
3. After user selected specification sections, program then uses the information it found from step 1 to query a database by filtering keywords to determine what products already exist for easy and rapid selection in the submittal process
4. Program then prompts the user with checkbox options for product-data submittals using information found from both step 1 & 3. Program also provides the option for user to input their own file paths for product-data not found on the database
5. Program then pieces together all product-data into a submittal format after user selects "Create", outputting the .pdf file to a name and location provided by the user

# TODO:
1. Create executable .JAR file which may involve moving around the Database
2. Add more database product-data options
3. Add option for user to input their own product-data .pdf file paths
4. Add a Table of Contents method and Title Sheet method in PDFwriter 
