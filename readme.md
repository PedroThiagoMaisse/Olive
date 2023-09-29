# Olive
This project ideia its to serve as a hub/dash of the status of my current projects.

The main ideia is being able to see current and recently runned pipelines, last updates, gather data, report error, check uptimes and current usage.


## Backlog


### 1. Structure
1. Set the http server 
2. Home page with a HTML response
3. Draw a base DB schema
4. Connect to a DB
    <details>

    - Get
    - Upload
    - Update

    </details>
5. Simple Running method
6. ~Git Flow~

### 2. Basis
1. Set APIKeys / login
    <details>

    - Different types of login
    - Being able to create new logins
    - Get keys from request query
        
    </details>
2. Easy way to config new projects
3. Route to recieve project error report
    <details>

    - Save Data
    - Display it on home page

    </details>
    
### 3. More Functionality
1. Way to call another another project test routes
    <details>

    - API
    - Git clone + test (maybe?)
    - Save Data
    - Display it on home page

    </details>
2. Get pipeline info
    <details>

    - Connect with providers
        - GitHub
        - AWS
        - Azure
    - Save Data
    - Display it on home page
    - if pipelines fails call the error route
    - When pipeline starts, call a report route
    - if pipelines succeed, call a report route

    </details>

3. Get last commits
    <details>

    - If i can see from where the pipeline was triggered, connect this to it
    - Display it on home page

    </details>


### 4. Even More (yay!)

1. Check Uptime
    <details>

    - When pipelines start, call a test route every x seconds to gather any downtime
    - When error route is called, call a test route every x seconds (until OK) to gather downtime
    - Call test route every x seconds (maybe?)
    - Connect with providers to check downtime registred
        - AWS
        - GitHub
        - Azure

    </details>

2. Check usage
    <details>

    - Connect with providers to check it registred
        - AWS
        - GitHub
        - Azure
    - Get it every x minutes

    </details>
