# mockexam
flask run command : 
      flask run --host=0.0.0.0 --port=3000 


create certificate:
     openssl req -x509 -newkey rsa:4096 -nodes -out asecert.pem -keyout asekey.pem -days 365

     
make https: 
    flask run --host=0.0.0.0 --port=3000 --cert=asecert.pem --key=asekey.pem
