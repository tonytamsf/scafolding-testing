## A webserver that will listen to http and redirects to https

### Use case
* To test whether a Podcast app will send the authorization header on a redirect
   * https://github.com/AntennaPod/AntennaPod/issues/5214

### Steps
1. `docker build -t http-https-redirect .`
2. docker run -p 80:80 http-https-redirect
3. Open browser to http://localhost:80/
4. you should see a redirect to https (port 443)
