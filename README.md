# phonedir

There are 4 directories:

##### To Check whether given numbers are Anagrams or not and group it and show the result.
        1. phonedir/phone-directory
        2. phonedir/phone-directory-mysql
        3. phonedir/ui

        ## RUN and Verify Phone Numbers in directory (Windows):
                
         ## Use Swagger UI for Update initial Data
            ## http://localhost:8080//swagger-ui.html
                ## 1. Find 'phone-directory-controller' text and click on it
                ## 2. Click On; "POST /api/v1/phones" link
                ## 3. Copy the content from phone-directory\src\main\resources\data_json.json file and Paste it in the 'Phones' value box
                ## 4. Click on the 'Try it out!' button in the same section.
                ## 5. 'GET /api/v1/all' : To see all Phone number details available in the dirctory
                ## 6. 'GET /api/v1/name/{name}' : To find phone details by {name}. Ex: http://localhost:8080/api/v1/name/hebbar
                                



                ## UI - Search Name by start to type on the Page.

                    ## Open index.html file in any of the browser
                    ## Start type on input box.


   ### Note: If you Type  'hebbar', Exepected Result :
                       ##  Name and Phone Number List ( Result: 5 ), Here  '5' indicates total numbers available in the directory
                       ##     
#Phone Number Datails: Result: 5
#Name          Phone Number

#Sooryanarayana Hebbar	9977224455
#Hebbar	8877660099
#Gururaj Hebbar	9972243215
#Saamya Hebbar	9972243225
#Shourya Hebbar	9972243230
                      