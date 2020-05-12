# sn-tdd-example

## GitHub
### Create token
    Open settings
    Click 'Developer Settings'
    Click 'Personal access tokens'
    Click 'Generate new token'
    Add Note to identify this token
    Select 'public_repo'
    Click 'Generate token'
    Make sure to copy your new personal access token now. You won’t be able to see it again!
  
    Fork this repository
    From your forked repository select 'Clone or Download'
    Copy Clone witth HTTPS URL

## ServiceNow
    Login in to instance
  
  ### Main Tab
    Open Studio

  ### Studio Tab
    Network protocol: 'http'
    URL: [URL from step ?]
    Branch: master
    Username: [GitHub username]
    Password: [Token from step ?]
    Click 'Import'
    Click 'Select Application'
    Open 'tdd'

  ### Main Tab
    Switch tto 'Global' applicattion
    Navigate to 'Automated Test Framework (ATF)' -> 'Administration' -> 'Properties'
    Select 'yes' for Enable test/test suite execution
    Click 'Save'
    
    Switch to 'tdd' applicattion
    Navigate to 'Automated Test Framework (ATF)' -> 'Tests'
    Open 'Data Plan' Test
    Open 'Run Server Side Script' to view Test Step
    Return to 'Data Plan' Test
    Click 'Run Test' (This should complete successfully)    
    

    
  
