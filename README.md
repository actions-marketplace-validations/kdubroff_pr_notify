# pr_notify
Create a PR and notify an email address or slack channel

inputs:

&nbsp;&nbsp;**serverAddress**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: "the email server's address"  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;&nbsp;&nbsp;default: 'smtp.gmail.com'  
&nbsp;&nbsp;**serverPort**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the port number used to login to your email server'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;&nbsp;&nbsp;default: '465'  
&nbsp;&nbsp;**emailAddress**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the email address used to login to your email server'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**emailPassword**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'password used to login to your email server'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**toEmailAddress**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the email address a notification email will be sent to'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**featureBranch**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'featureBranch: the branch being updated with sourceBranch'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**sourceBranch**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'sourceBranch: the branch being merged into featureBranch'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;&nbsp;&nbsp;default: 'develop'  
&nbsp;&nbsp;**name**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the name the email is from'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;&nbsp;&nbsp;default: 'Auto Merge Triage'  
&nbsp;&nbsp;**prURL**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: "the PR's URL"  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;&nbsp;&nbsp;default: 'https://github.com/NLSInc/Einstein-iOS/pulls'   
