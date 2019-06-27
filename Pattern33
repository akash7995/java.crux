public class MyClass {
    public static void main(String args[]) {
        int num = 7;
        int ns = 1;
        int count;
        for(int i = 1; i<=num; i++){
            for(int j = num-i; j>=1; j--){
                System.out.print(" ");
            }
            if(i==1){
                count = 0; 
            } else {
                count = (num - i) + 1;
            }
            for(int j = 1; j<=ns; j++){
                if(count==num){
                    System.out.print(0);
                } else{
                    System.out.print(count);
                }
                if(j<=ns/2){
                    count++;
                } else {
                    count--;
                }
            }
            System.out.println();
            
            ns = ns + 2;
        }
    }
}
