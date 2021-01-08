# webhook-with-jenkins

# Pre-requisites:
    Github Repo
    Jenkins setup
    Install Git
    Install Maven
# Add Jenkins URL in git hub as webhook
  Goto github --> settings --> webhook --> Add webhook
  Provide Jenkins url as shown in below image  but after port please specify the github-webhook its mandatory or else automatic build wont happen.
  
  
  
  ![image](https://user-images.githubusercontent.com/58024415/103783684-0c18d000-505f-11eb-8896-1a3036c2ac04.png)
  
  Click on Add Webook
  
  ![Capture](https://user-images.githubusercontent.com/54719289/104009295-d136a980-51d0-11eb-98cf-4ba0723a5ffc.JPG)
  
  After adding webhook,
  
  ![Capture](https://user-images.githubusercontent.com/54719289/104009429-08a55600-51d1-11eb-9274-3df584ea9e26.JPG)

  
# Create Jenkins job with Jenkinsfile content and click on GitHub hook trigger for GITScm polling as shown below

    Select Generic Webhook Trigger under Manage Plugin in Managejenkins
    Create freestyle project with test-webhook (any name)
    
  ![Capture](https://user-images.githubusercontent.com/54719289/104009522-37bbc780-51d1-11eb-9fe1-0b34469dfb62.JPG)
    
      
  
  
  Click on Build
  
  ![Capture](https://user-images.githubusercontent.com/54719289/104009690-70f43780-51d1-11eb-9401-af5efa37fcfd.JPG)
     


  No Build action in Jenkins but build happended automatically
  
# Change code in Github repo
  
  Build will happen automatically as show in below image
  
 ![Capture](https://user-images.githubusercontent.com/54719289/104009046-68e7c800-51d0-11eb-935f-690570ca91f7.JPG)



