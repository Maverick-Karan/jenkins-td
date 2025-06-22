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

System Design  
<img width="798" alt="image" src="https://github.com/user-attachments/assets/e6371ec7-cf8b-4917-ab17-d0fc9aa6cb61" />

======================================================================   
  
TASK 2: Implement CI/CD Pipeline Using Jenkins  

  Built 2 separate pipelines (backend and frontend)
<img width="1507" alt="image" src="https://github.com/user-attachments/assets/d0ce1c01-23c1-43a5-869b-38625733fd2d" />  

  Configured WebHook in github  
  <img width="1092" alt="image" src="https://github.com/user-attachments/assets/c34a9f31-ea53-4e9b-9130-6714388e1350" />  


  Successful build with configured Github Hook
<img width="713" alt="image" src="https://github.com/user-attachments/assets/383b97f9-e1f9-486c-8589-de82fdc85658" />  
<img width="686" alt="image" src="https://github.com/user-attachments/assets/9b07b34a-abc4-457e-8ec9-d1781ce30506" />



Used Jenkins Secrets to manage MongoDB credentials  
<img width="1381" alt="image" src="https://github.com/user-attachments/assets/c61ee265-1ea1-4f82-8d86-fbe60080271c" />  

  
Pipeline logs  
<img width="1502" alt="image" src="https://github.com/user-attachments/assets/5e686d89-d078-4b71-8be4-277553317fb0" />  
<img width="1491" alt="image" src="https://github.com/user-attachments/assets/dabf4c15-fc9a-43a9-9805-3ab8c6629be3" />  
<img width="1495" alt="image" src="https://github.com/user-attachments/assets/651edf4b-d3ea-4624-afb0-6c66555fd97c" />  
<img width="1499" alt="image" src="https://github.com/user-attachments/assets/360e5bda-ab39-4bf9-a492-bfdca229f7c0" />  
<img width="1494" alt="image" src="https://github.com/user-attachments/assets/8dec55ac-a76d-4066-a479-0f76a8cfbac6" />
<img width="1498" alt="image" src="https://github.com/user-attachments/assets/3d6408f2-75c3-49f2-8270-d0140e66f040" />  
<img width="1493" alt="image" src="https://github.com/user-attachments/assets/bbacf6cf-ebe5-428c-a4b0-da837d301d24" />
<img width="1492" alt="image" src="https://github.com/user-attachments/assets/54939b9b-9188-4a80-ba35-a04de1f62385" />


  Verify that both services are working in EC2 after the pipeline is successful  
  <img width="1461" alt="image" src="https://github.com/user-attachments/assets/78067321-7216-4ea5-8974-e6b761d0dca0" />  

  Test Application  
  <img width="355" alt="image" src="https://github.com/user-attachments/assets/70d04a06-9bc6-4def-a3e2-9c54159731a5" />
  <img width="417" alt="image" src="https://github.com/user-attachments/assets/6b3eb4b4-a4ae-4966-aab3-6c1c9ab0ce38" />  
  <img width="1301" alt="image" src="https://github.com/user-attachments/assets/fd39af54-1a08-451a-9fc8-1b307ff7e2f3" />

  












