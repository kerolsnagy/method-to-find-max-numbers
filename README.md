# method-to-find-max-numbers
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{

   static int max(int n1,int n2,int n3)
    {
        int maxNumber=n1;
        if (maxNumber < n2)
            maxNumber=n2;
        if (maxNumber < n3)
            maxNumber=n3;

            return maxNumber;
    }
    public static void main (String args[])
    {
        Scanner k=new Scanner(System.in);
        int x,y,z;
        System.out.println("Enter #1 :");
        x=k.nextInt();
        System.out.println("Enter #2 :");
        y= k.nextInt();
        System.out.println("Enter #3 :");
        z=k.nextInt();
        System.out.println("max =" +max(x,y,z));
    }
}

