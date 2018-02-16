# ADP Payslip Retriever

Usage with password prompt

```./payslip-retriever.sh -u USERNAME@COMPANY -e employee_number -o /path/to/output/dir```

Usage with password file:

```./payslip-retriever.sh -u USERNAME@COMPANY -p /path/to/password.txt -e employee_number -o /path/to/output/dir```

Crontab example to download payslip at 4am on the 17th of every month:

```0 4 17 * * /bin/bash /path/to/script/payslip-retriever.sh -u USERNAME@COMPANY -p /path/to/password.txt -e employee_number -o /path/to/output/dir```
