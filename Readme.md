# Dicoding Google Cloud Engineer

## Task 1

Deploy static page using App Engine and Cloud Storage

### Step

1. Create new bucket on Cloud Storage, ex: aic-dicoding-gce-task-1
2. Upload the images folder
3. Set permission to the images folder

   ```txt
   Principals: allUsers
   Role: Storage Object Viewer
   ```

4. Make sure the file is accessible, Click the images folder, Click a file, Open then Public URL
5. Create new app on App Engine
6. Open Cloud Shell, Click Open Editor
7. Upload project web
8. Open Terminal, go to the web project folder
9. Run `gcloud app deploy`

### Resource

- [https://templateflip.com](https://templateflip.com)
