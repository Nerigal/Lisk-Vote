# Lisk-Vote


Optimize your vote list for a minimum number of transaction vote queries  
Automatically exclude address from the list if you already votes for them to prevent error code return from the API 
Multiple Signature compatible 
Default test mode On... You have to confirm to make sure the transaction is apply.

# Add Voting mode

vote from a text file list based on lisk address 
`lisk-vote -HostUrl https://server.example.com -address 7499683620762904066L -Secret 'gsdfgsdfg' -SecondSecret 'agasdfasdf' -file 'C:\Users\whatever\documents\vote.log' -DataType address -verbose`

vote from a text file list based on Delegate Names
`lisk-vote -HostUrl https://server.example.com -address 7499683620762904066L -Secret 'gsdfgsdfg' -SecondSecret 'agasdfasdf' -file 'C:\Users\whatever\documents\vote.log' -DataType DelegateName -verbose`


# Remove Voting mode 

Remove from a text file list based on lisk address 
`lisk-vote -HostUrl https://server.example.com -address 7499683620762904066L -Secret 'gsdfgsdfg' -SecondSecret 'agasdfasdf' -file 'C:\Users\whatever\documents\devote.log' -DataType address -Remove:$true -verbose`

Remove from a text file list based on Delegate Names
`lisk-vote -HostUrl https://server.example.com -address 7499683620762904066L -Secret 'gsdfgsdfg' -SecondSecret 'agasdfasdf' -file 'C:\Users\whatever\documents\devote.log' -DataType DelegateName -Remove:$true -verbose`

 
