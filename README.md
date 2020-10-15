# java-programs-using-array
package com.Day2;

import java.util.Scanner;

public class main {

	public void Employee(String name, int age, String city) {

		System.out.println("The name is " + name);
		System.out.println("The age is  " + age);
		System.out.println("The city is " + city);

	}

	public static void main(String[] args) {

		Scanner values = new Scanner(System.in);

		System.out.println("Enter the name : ");
		String name = values.next();

		System.out.println("Enter the age : ");
		int age = values.nextInt();

		System.out.println("Enter the city : ");
		String city = values.next();

		main m = new main();
		m.Employee(name, age, city);

	}
}
