**ÖZYİNELEMELİ PALİNDROM KONTROLU**

Bu proje, Java dilinde özyinelemeli bir yöntem kullanarak bir metnin palindrom olup olmadığını kontrol eden bir uygulamayı içerir. Bir palindrom, baştan ve sondan okunduğunda aynı olan bir kelime veya cümledir.

**FONKSİYONLAR**

isPalindrome Metodu: Verilen bir string'in palindrom olup olmadığını kontrol eder. Bu metot, özyinelemeli bir yaklaşım kullanarak çalışır.

**ÖRNEK KULLANIM**

```java

public class PalidromKontrol {
    public static void main(String[] args) {
        // Örnek metinlerin palindrom olup olmadığı kontrol edilir
        String palindrome1 = "madam";
        boolean isPalindrome1 = isPalindrome(palindrome1);
        System.out.println(palindrome1 + " is a palindrome: " + isPalindrome1);

        String palindrome2 = "level";
        boolean isPalindrome2 = isPalindrome(palindrome2);
        System.out.println(palindrome2 + " is a palindrome: " + isPalindrome2);

        String notPalindrome = "java";
        boolean isPalindrome3 = isPalindrome(notPalindrome);
        System.out.println(notPalindrome + " is a palindrome: " + isPalindrome3);
    }

    // isPalindrome metodu buraya eklenecek
}
```

**KATKIDA BULUNMA**

Bu proje açık kaynaklıdır ve katkıda bulunmaya açıktır. Eğer bir hata bulursanız veya bir özellik eklemek isterseniz, lütfen bir pull isteği gönderin ya da bir issue açın.

