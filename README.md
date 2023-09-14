public class MatrixAndJaggedArrayDemo {
    public static void main(String[] args) {
        // Matrix (2D Array)
        int[][] matrix = {
            {1, 2, 3},
            {4, 5, 6},
            {7, 8, 9}
        };

        System.out.println("Matrix (2D Array):");
        for (int row = 0; row < matrix.length; row++) {
            for (int col = 0; col < matrix[row].length; col++) {
                System.out.print(matrix[row][col] + " ");
            }
            System.out.println();
        }

        // Jagged Array
        int[][] jaggedArray = {
            {1, 2},
            {3, 4, 5},
            {6}
        };

        System.out.println("\nJagged Array:");
        for (int row = 0; row < jaggedArray.length; row++) {
            for (int col = 0; col < jaggedArray[row].length; col++) {
                System.out.print(jaggedArray[row][col] + " ");
            }
            System.out.println();
        }
    }
}
