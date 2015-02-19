import java.util.*;
import java.lang.*;
import java.io.*;

class Ideone
{
	public static void main (String[] args) throws java.lang.Exception
	{
		int size = 8;
    int arr[] = {1, 2, 3, 5, 1, 3};
    int result[] = new int[size];

    for(int i =0; i < arr.length; i++)
    {
        if(result[arr[i]-1] == 1)
        {
            System.out.println("repeating: " + (arr[i]));
        }
        result[arr[i]-1]++;
    }

    for(int i =0; i < result.length; i++)
    {
        if(result[i] == 0)
        {
            System.out.println("missing: " + (i+1));
        }
    } 
	}
}
