# Introduction 
<b><big>bas-payloads</big></b> is an api based on <i>FastAPI<i> for return payload file to <b><big>bas-plugins</big></b> api
# Getting Started
1. Installation process
    <br> pip install -r requirements.txt
2. Software dependencies
<br> In next version this software have a docker configurations
3. Latest releases
4. API references
    <br> Api paramiter 
    <br> this link to file return http://localhost:8000/api/file/{file_name}
    <br> returning code 200 for sucess requisition
5. .env file examples <br>
    #BAS_VALIDATION <br>
    BAS_BACK_HOST=http://127.0.0.1:7000/token_validator <br>
    #Payload engine <br>
    PAYLOAD_DIR=/payloads <br>
    VOLUME_DIR=./data/payloads/


