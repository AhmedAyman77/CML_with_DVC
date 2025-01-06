## `Churn Detection with use of CML & DVC Tools `
    * Using different approaches for solving imbalancing dataset.
    * Using different Algorithms also.
-----------------------------------------------------------------
## `DVC Installation`
``` bash
pip install dvc
pip install dvc-gdrive  # for using gdrive
```

### Git
``` bash
git init
git add .
git commit -m "initial commit"
git remote add origin <ssh or http link>
git push

git pull
git status
```

### DVC
``` bash
dvc init
dvc add data.csv
dvc remote add --default myremote gdrive://<fodler-id> # if using gdrive
# to push without asking for authentication
dvc remote modify your_dvc_remote_name gdrive_use_service_account true
dvc remote modify your_dvc_remote_name gdrive_service_account_json_file_path "path/to/json/file"
dvc push

dvc status
dvc doctor

# to get the original folders/files
dvc pull

```


``` bash
# find the default.json file credentials
C:\Users\YourUsername\AppData\Local
```# CML_with_DVC
