# Email Verification Tool
This is a project built with Golang. A simple tool where one can verify an email addresses' doamin.


## Technologies Used
* Golang

## Dependencies
* Install Go - https://go.dev/doc/install

## Executing program
* Download the repository to your computer and go to project file
```
git clone https://github.com/sayedh/email-checker-tool
cd email-checker-tool
go run main.gp
```

* Specify the domain of the email address
```
go run main.go
domain,hasMX,hasSPF,sprRecord,hasDMARC,dmarcRecord
outlook.com  
```
