

# Create service principal
az ad sp create-for-rbac --name github-sp --role contributor  --scopes /subscriptions/<subscription-id>  --sdk-auth

#  Repo → Settings → Secrets and Variables → Actions → New repository secret
# save both 
   AZURE_CREDENTIALS
   SSH_PRIVATE_KEY
