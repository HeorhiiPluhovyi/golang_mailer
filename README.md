#### 1. Create README.md
```bash
touch README.md
```

#### 2. Create .env
```bash
touch .env
```
#### and add fields
```
EMAIL=your_emain
PASSWORDS=your_password
SMTPHOST=your_smtp_host
SMTPPORT=your_smtp_port
RECEIVER=receiver_email
```

#### 3. Create .gitignore
```bash
touch .gitignore
```
### Add .idea, .env
```gitignore
.idea
.env
```

#### 4. Enable dependency tracking for your code
```bash
go mod init HeorhiiPluhovyi/golang_mailer.git
```

#### 5. Creating main file  
```bash
touch main.go
```

#### 6. Add godotenv package
```bash
go get github.com/joho/godotenv
```

#### 7. Create template.html
```bash
touch template.html
```
