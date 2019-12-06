# Run PyTorch Deeplearning framework in GCP


### create Deeplearning VM in GCP
##### 1.search "Deep Learning VM" on GCP Marketplace
##### 2.select the first one which name is "Deep Learning VM"
##### 3.configure the instance 

##### 4.you need to wait for few minutes, the system need time to cogifg

##### 5.when the configuration finish, you will find the "Suggested next steps" in the right side, which give you some instruction of how to upload files to this Deep Learning VM.

###### Firstly, you need to make sure Cloud SDK has been installed in your local computer
###### If bot, follow this instruction:https://cloud.google.com/sdk/install

###### Then you can copy files to your VM from your local machine.
gcloud compute scp --project cloud-association --zone australia-southeast1-a --recurse <local file or directory> deeplearningmodel-vm:~/
  
  
###### Access the running Jupyter notebook.
###### If you are not sure how to set up Jupyter-notebook on GCP VM, please refer the following instruction
https://towardsdatascience.com/running-jupyter-notebook-in-google-cloud-platform-in-15-min-61e16da34d52
