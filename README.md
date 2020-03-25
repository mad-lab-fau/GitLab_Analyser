# GitLab_Analyser

###################### 1. Requirements ######################

- Git must be installed. Information on how this can be done can be found here:
(https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

- For Windows: Care must be taken that Git can be called from the Windows Command Prompt 
(Adjustable during installation under the adjustment of PATH environment step)

###################### 2. Preparation for analysis: ######################

- Create an save a GitLab Personal access token 
https://docs.gitlab.com/ee/user/profile/personal_access_tokens.html)

- open the token_info.json file that lies in the same directory as the main.exe tool file

- enter the base URL of your GitLab repositorys that you want to analyze (e.g. https://<your-gitlab-repo-url>.de/)

- enter the saved access token created in the step before

- save and close the token_info.json (do NOT move the file. It must be in the same directory as the main.exe)

- clone and save the Git and Wiki repositories of the GitLab project you want to analyze on your local device
(See: https://git-scm.com/docs/git-clone)

###################### 3. Start the Tool ######################

- Start the Tool with the main.exe 

- if an error ocurred or the tool does not start, check the URL and token in step 2 to be correct

- select your analysis type (single, group, cross-project)

- when the analysis type is selected enter your GitLab base URL (similar to the one from step 2)

- when the URL is correct and matches the one entered in the token_info.json the available projects will be fetched

- after a view seconds select the fetched projects to be analyzed

- (only for single project analysis): selected the cloned Git and Wiki repositories (step 2) via the provided selection options 

- (only for single project analysis): select the Git branch to be considered in the analysis

- (optional) set the checkbox if results from a previous  run should be used.
If not uncheck it and a new data extraction will be performed (takes up to 15min depending on project size)

- (optional) if a certain time period should be analyzed mark the timeboxed analysis checkbox,
define the timerange via the datepicker and add it via the plus-icon

- press start analysis 

- if results from previous runs are used the results will be ready after a view seconds
A new analysis including completely new data extraction might take up to 15 min depending on the project size

###################### 4. Result views ######################

- Project view: all data and information about the whole GitLab project

- Project user view: Results for each project participant

- Group Git: Information about the groups Git participation, handling, performance, etc.

- Group Wiki: Information about the groups Wiki participation, handling, performance, etc.

- User Git: Information about the individual user's Git participation, handling, performance, etc.

- User Wiki: Information about the individual user's Wiki participation, handling, performance, etc.

###################### HAPPY ANALYZING! ###################### 
