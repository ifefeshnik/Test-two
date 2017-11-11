//# Test-two;
//Test Break;


import java.util.*;
import java.lang.*;

public class Break {

    public static int[] range(int n) {
        int[] result = new int[n];
        for(int i = 0; i < n; i++)
            result[i] = i;
        return result;

    }
    public static void main (String[] args){
        for (int i =0;i<100;i++){
            if (i==74) break;
        if(i%9!=0)continue;
        System.out.print(i+" " );
        }
        System.out.println();
        for ( int i  : range(100)) {
           if (i==10) break;
           if (i%9!=0)continue;
           System.out.print(i+ " ");
        }
        System.out.println();
        int i=0;
        while (true)
        {
            i++;
            int j = i*27;
            if(j==1269)break;
            if (i%10!=0)continue;
            System.out.print(i+ " " );
            System.out.print(i+  " "+i );
        }
    }
}
