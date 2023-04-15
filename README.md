<h1>S3 Uploads Configuration for Storj</h1>

This plugin is designed to work with <a href="https://www.storj.io/">Storj</a>. You need configure it via environment variables in file <code>index.js</code> as shown below.

<h3>Variables:</h3>
<pre><code>
AWS_ACCESS_KEY_ID="your access key"
AWS_SECRET_ACCESS_KEY="your secret access key"
S3_ACCESS_GRANT="your access grant key"
S3_ENDPOINT="gateway.storjshare.io"
S3_UPLOADS_BUCKET="your bucket name"
S3_UPLOADS_HOST="gateway.storjshare.io"
S3_ALIAS_HOST="link.storjshare.io/raw"
</code></pre>

File URL is formed as follows: <code>https://ALIASHOST/ACCESSGRANT/BUCKET/files/image.png</code>

If you need help, create an <a href="https://github.com/ferumdev/nodebb-plugin-storj-upload/issues/">issue on Github</a>

<br>

💙 **Thanks**

This plugin was creates on based a plugin [NodeBB S3 Uploads Plugin](https://www.npmjs.com/package/nodebb-plugin-s3-uploads-updated-again).