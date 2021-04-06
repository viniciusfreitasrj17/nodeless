# Install Serverless
sudo npm install -g serverless

# Create Project
serverless create --template aws-nodejs --path nodeless

# Configure IAM
serverless config credentials -o --provider aws --key xxx --secret xxx

# Deploy Serverless
serverless deploy -v

# Invoke Function
serverless invoke -f hello -l

# Remove Serverless
serverless remove