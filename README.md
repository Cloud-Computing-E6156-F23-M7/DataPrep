# DataPrepApp

## Install Necessary Packages

In DataPrep folder
```
source venv/bin/activate

brew install node
npm install --save axios
```

## In DataPrep/backend folder
```
<install from Docker website> https://docs.docker.com/desktop/install/mac-install/

pip install -r requirements.txt

<Reset the databases> remove instance directory and run python "app.py"

docker build -t sample-backend .
docker run -p 8080:8080 sample-backend
```

## In DataPrep/frontend folder (not implemented)
```
export NODE_OPTIONS=--openssl-legacy-provider
export REACT_APP_API_URL=http://localhost:8080/api

npm start
```
