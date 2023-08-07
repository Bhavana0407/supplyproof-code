# supplyproof-code

Requirements : 
1. Docker Desktop 4.16.3
2. Android Studio 2022.2
3. Nodejs v12.22.9

Blockchain Establishment :
1. Open docker.
2. Open command prompt ( ubuntu terminal)
3. Navigate to supplyproof/network directory.
4. ./network.sh createChannel
5. In a new terminal, navigate to chaincode/files
6. Open wallet & delete all the files present.
7. Run following commands one by one: 
  --> node enrollAdmin.js  //To enroll admins for all the organisations
  --> node registerFarmer.js  // To register a test farmer user
  --> node registerLogistics.js  // To Register a test logistics user
  --> node registerWarehouse.js  //To register a test warehouse user
  --> node registerBuyer.js  // To register a test buyer user
  --> node node.js  // Starting node.js server

Running the app :
1. Open android studio.
2. Run the app.
