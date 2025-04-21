# 3tier-application
deploy 3-tier application in ec2 

# 3-tier application: 
Frontend: ReactJS
Backend: NodeJS
Database: MongoDB

git clone _repo-link-paste-here_

**** For backend-------------------
-- check node version 
node -v 
npm -v

---if not then download it from its official website
https://nodejs.org/en/download

-- after donwloding node go to backend and install npm package
cd backend
npm i

**** For MongoDB --------------------
--- download MongoDB from its official website for linux 
https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-ubuntu/#std-label-install-mdb-community-ubuntu

--- check mongodb by 
mongosh 

---- IMPORT THE SAMPLE DATA FROM JSON FILE
---copy data from .env.sample to .env file
cp .env.sample .env

--- to run backend server 
npm start 

**** for frontend -------------------------
--- to run npm i for install node package manager 
npm i

---copy sample file to .env.local file of frontend  
cp .env.sample .env.local

--- to run the frontend  
npm run dev 

// that give local addres:port-no.
// expose it to add --host 
npm run dev -- --host &

--- to add backend to frontend 



