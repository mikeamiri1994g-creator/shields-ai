mkdir shields-ai
cd shields-ai
git init
git branch -M main

# Create files (copy code from previous)
cat > shields_security_ai.py << 'EOF'
[PASTE FULL UPDATED CODE HERE]
EOF

cat > README.md << 'EOF'
# Shields Security AI
AI cyber tool. $19/mo. PayPal @moneyyyman888
EOF

git add .
git commit -m "initial"
git remote add origin https://github.com/YOURUSERNAME/shields-ai.git
git push -u origin main
