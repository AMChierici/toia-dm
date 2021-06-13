# toia-dm

Make sure to edit the code in the src folder to replace the real database in the global variable SQL_URL

Install Conda environment using
```bash
conda env create -f environment.yml
```

And run Flask app:
```bash
python src/app.py
```

Test using GET request to /dialogue_manager route, send json with body like below:
```json
{
    "query" : "what do you do",
    "avatar_id" : "1"
} 
```

![alt text](https://github.com/AMChierici/toia-dm/test/img/postman.png "Postman screenshot")

