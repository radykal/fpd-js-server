# fpd-js-server
Here you find helpful server libraries to enable file uploads with Fancy Product Designer.

## PHP
Download the php folder and upload to the folder your web server.

### File Upload
Open `file-handler.php` and edit the first 2 variables:

`$uploads_dir`: Change to a local path where you want to upload the files to.
`$uploads_dir_url`: Change to the public url of that uploads folder, e.g. `https://yourdomain.comm/uploads
`

### Instagram Token URI
In order to enable the Instagram feature in the product designer. The authentication for your users requires some server processing. 

Open `instagram-token.php` and add your Instagram client secret in the `$client_secret` variable. 

## NodeJS
Coming soon...