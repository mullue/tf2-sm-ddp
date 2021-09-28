* Clone https://github.com/mullue/tf2-sm-ddp/tree/tfddp-studio-version
* Create a s3 bucket to be used by the Cloud Formation Template
* cd sagemaker-studio-version
* make deploy CFN_ARTEFACT_S3_BUCKET=<your s3 bucket>
* Open the Sagemaker Studio session created in the above step
* Clone https://github.com/mullue/tf2-sm-ddp/tree/tfddp-studio-version into Sagemaker Studio
* Use tf2-sm-ddp/sagemaker-studio-version/tf2-mrcnn-dataparallel.ipynb for the workshop
