/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author ASUS
 */
class Manusia{
    
    public void Siapa_saya(){
        System.out.println("Saya Manusia");
        
    }
    
}
 class Dosen extends Manusia {
     public void Nip(){
         System.out.println ("NIP Dosen : 41227829930" );
     
 }
     
     public void Siapa_saya(){
         System.out.println("Saya  Dosen");
     }
     public void Mengajar_apa(){
         System.out.println("Saya Rizki Adam Kurniawan 27 Tahun sedang mengajar  mata kuliah PBO");
     }
     
 }
class Mahasiswa extends Manusia{
    public void nim(){
        System.out.println("NIM MAHASISWA : 10110269");
    }
    public void Siapa_Saya(){
        System.out.println("Saya Mahasiswa");
    }
    public void Kelas_apa(){
        System.out.println("Saya Nindi umur 17 Tahun sedang belajar di Kelas PBO2");
    }
}

public class Latihan52 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
       Dosen Rizki = new Dosen();
       Mahasiswa Nindi = new Mahasiswa();
     Rizki .Nip();
     Rizki.Siapa_saya();
     Rizki.Mengajar_apa();
     System.out.println("");
     
     Nindi.nim();
     Nindi.Siapa_Saya();
     Nindi.Kelas_apa();
       
    }
    
}
