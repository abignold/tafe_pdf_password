git clone https://github.com/abignold/tafe_pdf_password.git
cd tafe_pdf_password
pdf2john protected.pdf > hash
cat hash
john --wordlist /usr/share/wordlists/rockyou.txt.gz hash