How to Launch

1. Cleanup existing dockers
************************************************
./Team_4_cleanup.sh    

2. Launching the dockers and installing chaincode
*************************************************
 cd medicine-track-app/
 ./start.sh
 ./setup.sh

3. Launching the node modules
*************************************************
cd medicineTrack-api/
rm hfc-key-store/*
rm package-lock.json
npm install
npm start


