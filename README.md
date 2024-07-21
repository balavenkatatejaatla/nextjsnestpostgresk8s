# project



---

1. **Configure AWS CLI**: `aws configure` (set up credentials in `~/.aws/credentials`).
2. **Update Kubernetes Config**: `aws eks update-kubeconfig --region us-east-2 --name test-ekscluster --profile Teja`.
3. **Deploy with Terraform**: `terraform init && terraform plan && terraform apply --auto-approve`. ( Note - Run this in terraform folder )

---


-----------------------------------------
To run locally below are the commands that run in the respective folders

nest run - npm run start:dev
nextjs - npm run dev


sudo apt install postgresql-client

psql -h localhost -U myuser -d myapp

\dt
SELECT * FROM messages;

error
permission issue

sudo systemctl restart postgresql

sudo -i -u postgres
psql

-- Switch to the 'myapp' database
\c myapp;

-- Grant all privileges on the 'messages' table to 'myuser'
GRANT ALL PRIVILEGES ON TABLE messages TO myuser;


\dp messages;

\q

\dp messages;

