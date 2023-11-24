# java-diamond-pattren
java star pattren of diamond shape 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------




source code    

    public class diamondpattren {  
    public static void main(String[] args) {
        //above traingle of diamond
        for(int i =1;i<=5;i++){
            for(int j=1;j<=5;j++){
        
                if(i+j>5)
                System.out.print(("* "));
            else
            
            System.out.print("  ");
            }
            for(int k=1;k<=5;k++){
            
            if(i<=k)
            System.out.print(("  "));
            else
            System.out.print("* ");
            }

            System.out.println("");
            
            //lower triangle 

        } for(int m =1;m<=4;m++){
            for(int n=1;n<=5;n++){
                if(m<n)
                System.out.print(("* "));
            else
            System.out.print("  ");
            }
            for(int o=1;o<=3-m+1;o++){
                System.out.print("* ");
            }

            System.out.println("");
    }
    }}
