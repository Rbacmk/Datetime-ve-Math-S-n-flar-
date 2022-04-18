# Datetime-ve-Math-S-n-fları 
 // Datetime ve Math Sınıfları
           Console.WriteLine(DateTime.Now);//Günün tarihi getirir.
            Console.WriteLine(DateTime.Now.Date);// Günün tarihini getiriyor.
            Console.WriteLine(DateTime.Now.Day);//Günü getiriyor.
            Console.WriteLine(DateTime.Now.Month);// Günün ayını getiriyor.
            Console.WriteLine(DateTime.Now.Year);// Günün yılını getiriyor.

            Console.WriteLine(DateTime.Now.Hour);// Günün saatini getiriyor.
            Console.WriteLine(DateTime.Now.Minute);// Günün dakikasını getiriyor.
            C
            onsole.WriteLine(DateTime.Now.Second);// Günün saniyesini getiriyor. 
            
            
 Console.WriteLine(DateTime.Now.DayOfWeek);// String halde getirir.- Cumartesi.
            Console.WriteLine(DateTime.Now.DayOfYear);// Yılın kaçıncı günündeyiz?
            Console.WriteLine(DateTime.Now.ToLongDateString());//
            Console.WriteLine(DateTime.Now.ToShortTimeString());

            Console.WriteLine(DateTime.Now.AddDays(2));// Gün ekler.
            Console.WriteLine(DateTime.Now.AddHours(3));// Saat ekler.
            Console.WriteLine(DateTime.Now.AddSeconds(30));// Saniye ekler.
            Console.WriteLine(DateTime.Now.AddMonths(5));// Ay ekler.
            Console.WriteLine(DateTime.Now.AddYears(10));// Yıl ekler.
            Console.WriteLine(DateTime.Now.AddMilliseconds(50));
            Console.ReadLine();


 // DATETİME FORMAT
            Console.WriteLine(DateTime.Now.ToString("dd"));//24
            Console.WriteLine(DateTime.Now.ToString("ddd"));// Sat
            Console.WriteLine(DateTime.Now.ToString("dddd"));// Saturday

            Console.WriteLine(DateTime.Now.ToString("  MM"));//04
            Console.WriteLine(DateTime.Now.ToString("MMM"));// Apr
            Console.WriteLine(DateTime.Now.ToString("MMMM"));// April

            Console.WriteLine(DateTime.Now.ToString("yy"));//21
            Console.WriteLine(DateTime.Now.ToString("yyyy"));// 2021

            // MATH KÜTÜPHANESİ
            Console.WriteLine(Math.Abs(-25));// 25 (Tam tersi)
            Console.WriteLine(Math.Sin(10));// Sin karşılığını verir.
            Console.WriteLine(Math.Cos(10));
            Console.WriteLine(Math.Tan(10));
            Console.WriteLine(Math.Ceiling(22.3));//22.3 büyük en küçük tan sayıyı getiriyor.
            Console.WriteLine(Math.Round(22.3));// Hangi sayıya daha yakınsa.-22.
            Console.WriteLine(Math.Floor(22.7));//22

            Console.WriteLine(Math.Max(2, 6));//İki sayının minimum ve maximum değeri söyler.
            Console.WriteLine(Math.Min(2, 6));
            Console.WriteLine(Math.Pow(3, 4));// 3 üzeri 4'ü verir.81.
            Console.WriteLine(Math.Sqrt(9));// Karekök alır.
            Console.WriteLine(Math.Log(9));// 9 un e tabanındaki karşılığını getirir.
            Console.WriteLine(Math.Exp(3));// e üzeri 3 ü verir.
            Console.WriteLine(Math.Log10(10));// 10 sayısının logaritma 10 tabanındaki karşılığını verir.
