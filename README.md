# Shark_Tank_Scrap

Sony TV is back with another new show named Shark Tank India which is based on America’s show Shark Tank.  Shark Tank India is a business reality show were entrepreneurs pitch and introduce their business model or idea to the Sharks.

Scrap_Link : https://www.serialupdates.me/shark-tank-india-investors-names-sony-tv-new-show-entrepreneurs-list/

Table_Name : Shark Tank India Entrepreneurs – Offers


Procedure: -
Step1.Import necessary library

Step2.The Url of the website to be scraped to be imported into the jupyter file

Step3.Change the current directory on the install path of webdriver.

select geckodriver-v0.30.0-win64.zip file.-> used to run webbrowser on remote server

coping above file and pasting in different directory with folder -> 'script webdriver' is used to automate remotly to open -> fetch url directly from selenium.

then create new notebook and change directory in notebook to webdriver folder

open a firefox browser(using selenium webdriver) -- >

load page -->

get html


step4.page_source method is used retrieve the page source of the webpage the user is currently accessing. The main use of this method to find something in the page source like finding any data or keyword.

Step5.Beautiful Soup is powerful because our Python objects match the nested structure of the HTML document we are scraping.
Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.

Step6.Using find_all() to scrape data

Step7.Using find_all() to access specific/unique div tags

Step8.Requests-> allows you to send HTTP using python coding

Step9.To do this we need to stimulate a browser using tool called -> selenium webdriver
    --Its a Tool used for automating web browsers to do a number of tasks.
    --One of such task is web-scraping to extract useful data for dynamic webpages
    
Step10.Steps:

    Select Parent <table> tag
    select children tags of <table> which are <thead> and <tbody>
    
    
table>
        <t-head> //table columns
    
            <tr>
                
               
                <th>
                    
                    table column name
                    
                </th>
            </tr>
    
        </t-head>
        
        <tbody> //table row data
        
            <tr>
            
                <td>
                
                    all the required data
                    
                </td>
                
            </tr>
            
        </tbody>
        
    </table>
    
 Step11: Once scraped, store the data in DataFrame and Convert the DataFrame into .csv file.
