package com.company;

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        String fname;
        String lname;
        double gpa;

        Scanner keyboard = new Scanner(System.in);

        System.out.print( "Student's First Name? " );
        fname = keyboard.next();

        System.out.print( "Student's Last Name? " );
        lname = keyboard.next();

        System.out.print( "Student's GPA? " );
        gpa = keyboard.nextDouble();

        System.out.println();
        System.out.println("Student Name :" + fname + " " + lname);
        System.out.println("Student GPA :" + gpa);


        if (gpa >= 3)
        {
            System.out.println("This student is in good standing.");
        } if  (gpa == 1)
        {
            System.out.println("This student is on academic probation.");
        } if (gpa <1)
        {
            System.out.println("This student has been expelled.");
        }
    }
    }

