# -MATIX-3D-ARRAY-
public class Matrix3DArray {
    public static void main(String[] args) {
        // TODO code application logic here
        int[][][]array={
            {
                {3,5,9},
                {12,7,2}
            },
            {
                {4,6,8},
                {10,14,1}
            }
        };
        int max=array[0][0][0];
        for (int [][] matrix: array){
            for(int[] row :matrix){
                for(int element:row){
                    if (element>max){
                        max=element;
                    }
                }
            }
        }
        System.out.println("Maximun elememnt in 3D aaray:"+max);
    }
    
}

O/P

Maximun elememnt in 3D aaray:14

