1                                1
12                              21
123                            321
1234                          4321
12345                        54321
123456                      654321
1234567                    7654321
12345678                  87654321
123456789                987654321
12345678910            10987654321
1234567891011        1110987654321
123456789101112    121110987654321
1234567891011121313121110987654321



import java.util.*;

class rough{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter the size of the pyramid : ");
        int n = sc.nextInt();

        if(n<=9){
            for(int i = 1; i<=n; i++){
                for(int j=1; j<=i; j++){
                    System.out.print(j);
                }
                for(int k=1; k<= 2*(n-i) ;k++){
                    System.out.print(" ");
                }
                for(int j=i; j>=1; j--){
                    System.out.print(j);
                }
                System.out.println();
            }
        }
        //--------------------------------------------

        else if(n>9 && n<100){
            for(int i = 1; i<=n; i++){
                for(int j= 1; j<=i ; j++){
                    System.out.print(j);
                }
    
                if(i>=9){
                    for(int k=1; k<= 4*(n-i) ; k++){
                        System.out.print(" ");
                    }
                }
                else{
                    for(int k=1; k<= 4*(n-9) + 2*(10-i-1) ; k++){
                        System.out.print(" ");
                    }
                }

                for(int j= i; j>=1 ; j--){
                    System.out.print(j);
                }
                System.out.println();
            }
        }
    }
}
