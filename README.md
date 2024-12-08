# Array-Recursion
Array using Recursion in java
public class RecurrsionArray {
    public RecurrsionArray() {
    }

    static void printArray(int[] arr, int idx) {
        if (idx != arr.length) {
            System.out.println(arr[idx]);
            printArray(arr, idx + 1);
        }
    }

    public static void main(String[] args) {
        int[] arr = new int[]{5, 6, 7, 8, 9};
        printArray(arr, 0);
    }
}
