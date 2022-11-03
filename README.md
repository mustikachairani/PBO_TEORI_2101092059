# PBO_TEORI_2101092059

public class latihan1 {
    public static void main(String[]args)
    {
        String[] hari = { "Senin","Selasa","Rabu","Kamis","Jumat","Sabtu","Minggu"};

        int i=0;
        do
            {
                System.out.println(hari[i]);
                i++;
            }while(i<hari.length);
    }
}

public class latihan2 {
    public static void main(String[]args)
    {
        BufferedReader masukan = new BufferedReader(new InputStreamReader(System.in));
        int[] a = new int[11];
        int terbesar = 0;
        for(int i=1;i+1<=a.length;i++)
        {
            System.out.println("Masukkan angka "+i+" :");
            try
            {
                a[i] = Integer.parseInt(masukan.readLine());
            }
            catch( IOException e)
            {
                
            }
            if(terbesar>a[i])
            {
                if(terbesar>a[i])
                {
                terbesar=terbesar;
                }
            }
            else
            {
                if(a[i]>a[i-1])
                {
                terbesar=a[i];
                }
                else
                {
                terbesar=a[i-1];
                }
            }
        }
        String hasil="Terbesar adalah "+terbesar;
        System.out.println(hasil);}
}

public class latihan3 {
    public static void main(String[] args) {
     String alamat[][] = {{"Florence", "735-1234", "Manila"}, {"Joyce", "983-3333", "Quezon City"},{"Becca", "456-3322", "Manila"}};
        int i=0;
        do{
            System.out.println("name    :" + alamat[i][0] );
            System.out.println("Tel. #  :" + alamat[i][1] );
            System.out.println("Address :" + alamat[i][2] );
            System.out.println(" ");
            i++;
          }
        while (i<3);
    }
}
