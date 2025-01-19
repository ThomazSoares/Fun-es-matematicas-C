{

    int mdc(int a, int b){
        int i = 1;
        int maiorzin = 1;
        
        while (a / i >= 1 && b / i >= 1){
            if (a % i == 0 && b % i == 0){
                maiorzin = i;
            }
            
            i++;
        }
        
        return maiorzin;
    }
}
{

    int eh_primo(int num){
        int i = 2;
        int ehs_primo = 1;
        
        while (num / i >= 2){
            if (num % i == 0){
                return 0;
                ehs_primo = 0;
            }
            
            i++;
        }
        
        if (ehs_primo == 1 && num != 1){
            return 1;
        }
    }
}
