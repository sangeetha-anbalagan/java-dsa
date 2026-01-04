// create 1d row amd column
//where the zero is present put row and column value is 1

class Solution {
    public void setZeroes(int[][] matrix) {
        boolean []row=new boolean[matrix.length];
        boolean[]col=new boolean[matrix[0].length];
        for(int i=0;i<matrix.length;i++){
            for(int j=0;j<matrix[0].length;j++){
                if(matrix[i][j]==0){
                    row[i]=true;
                    col[j]=true;
                }
            }
        }
        for(int i=0;i<matrix.length;i++){
            for(int j=0;j<matrix[0].length;j++){
                if(row[i]==true||col[j]==true){
                    matrix[i][j]=0;
                }
            }
        }
        for(int i=0;i<matrix.length;i++){
            for(int j=0;j<matrix[0].length;j++){
                System.out.print(matrix[i][j]);
                }
                 }  
    }
}
