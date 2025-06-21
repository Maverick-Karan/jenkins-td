TASK 1:  
Deploy Flask and Express on a Single EC2 Instance  
  
Created EC2 - ubuntu  
<img width="1510" alt="image" src="https://github.com/user-attachments/assets/f34d405b-2c2e-4055-922f-baae50ef0191" />  

SSH into EC2  
<img width="585" alt="image" src="https://github.com/user-attachments/assets/4e358d35-d5e0-4bea-a2ee-189cc6159c4c" />  

Install basics:  
sudo apt install -y python3-pip python3-venv nodejs npm git  
<img width="313" alt="image" src="https://github.com/user-attachments/assets/aeb3b727-18fb-410d-b052-b1c2ab3aaeb8" />  

Git clone  
<img width="595" alt="image" src="https://github.com/user-attachments/assets/2091b158-a8dd-408f-b87f-de0321eaedf9" />  

Install dependencies:  
--- Backend ---  
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt  

--- Frontend ---  
npm install  

Created services for the frontend and backend  
<img width="447" alt="image" src="https://github.com/user-attachments/assets/e2c16f47-df31-4322-8f94-525ffaeb57a0" />  
<img width="614" alt="image" src="https://github.com/user-attachments/assets/2bf3e08d-640b-4b73-9265-08fcf0e7e2c1" />

Started frontend and backend using systemd  
<img width="919" alt="image" src="https://github.com/user-attachments/assets/4ce21b6a-6a93-4a57-8690-18379957d1e0" />  

Accessing the frontend using the public IP  
<img width="374" alt="image" src="https://github.com/user-attachments/assets/3cd84db8-d07e-4691-9ef2-6b264534c019" />  
<img width="329" alt="image" src="https://github.com/user-attachments/assets/cc377cf2-060c-47f5-a881-9a1e9cdae722" />  
<img width="958" alt="image" src="https://github.com/user-attachments/assets/40ca8d5c-6de2-4b6e-821a-7dc73d861580" />










