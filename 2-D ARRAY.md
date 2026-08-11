# DSA-JAVA-
lass Main {
      public static void main(String[] args) {
    int arr[][]={{33,34,35},{36,37,38},{39,40,41}};
    for(int i=0;i<arr.length;i++){
        for(int j=0;j<arr[0].length;j++){
            System.out.println(arr[i][j]);
        }
    }
}
}
33
34
35
36
37
38
39
40
41

DIGONAL SUM 
// Online Java Compiler
// Use this editor to write, compile and run your Java code online

class Main {
      public static void main(String[] args) {
        int sum=0;
    int arr[][]={{33,34,35},{36,37,38},{39,40,41}};
    for(int i=0;i<arr.length;i++){
        for(int j=0;j<arr[0].length;j++){
            if(i==j){
                sum= sum+arr[i][j];
                  
            }
          
        }
    }
    System.out.println(sum);
}
} 
111
