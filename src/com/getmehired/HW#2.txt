package com.getmehired;

public class Arraydemo {

    public static void main(String[] args) {
	// write your code here
        int[] anArray; // declare an array of integers
        anArray = new int[10]; //create an array of integers

        //assign a value to each array element & print
        for ( int i=0; i<anArray.length; i++) {
            anArray[i] = i;
            System.out.print(anArray[i] + " ");
        }
        System.out.println();
        int firstArray[] = new int[] {0,1,2,3,4,5,6,7,8,9};
        int secondArray[] = new int[10];
        int i = 0;
        secondArray[i] = firstArray[i];
        System.out.println(secondArray[i]);

        //now i want to replace 3rd element of first array
        // "introduction to algorithm"
        System.out.println("firstArray before replace:" + firstArray);
        firstArray.set(2,"introduction to algorithms");
        System.out.println("firstArray after replace:" + firstArray);
    }
}
