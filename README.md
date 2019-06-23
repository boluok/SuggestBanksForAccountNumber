# Suggest Banks For AccountNumber
This is a swift implementation of an algorithm that tells you the possible Nigerian banks that a bank account number may belong to

## Getting Started
A Nigerian bank has a `Name` , `Bank Code` , `Nuban Code`  and this is what we will be operating with

    class Bank{
        var bankname : String
        var bankcode :String
        var nubancode : String
        init(bankname:String,bankcode:String,nubancode:String) {
            self.bankcode = bankcode
            self.bankname = bankname
            self.nubancode = nubancode
        }
    }
		
		
