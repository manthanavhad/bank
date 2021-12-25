void Bank::open_account()
{
    name = "xyz Gupta";
    cout << "Enter your full name: "
         << name << endl;
    address = "Banglore";
    cout << "Enter your address: "
         << address << endl;
    acc_type = 'S';
    cout << "Type of account you want "
         << "to open saving(S) or Current(C): "
         << acc_type << endl;
    balance = 8000;
    cout << "Enter the amount for deposit: "
         << balance << endl;
    cout << "Account Created Successfully";
}
