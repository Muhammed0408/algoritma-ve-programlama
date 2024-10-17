# algoritma-ve-programlama
kod işlem süreleri

#include <stdio.h>#include <time.h> 
int main() { 
clock_t start = clock(); 
printf("Merhaba MIS, algoritma ve programlama\n"); 
clock_t end = clock(); 
double time_spent = (double)(end - start) / 
CLOCKS_PER_SEC; 
printf("C işlem süresi: %f saniye\n", time_spent); 
return 0; 
} 
Merhaba MIS, algoritma ve programlama 
C işlem süresi: 0.000075 saniye using System; 
 
using System.Diagnostics; 
class Program 
{ 
static void Main() 
{ 
Stopwatch stopwatch = new Stopwatch(); 
stopwatch.Start(); 
Console.WriteLine("Merhaba MIS, algoritma ve programlama dersi başladı"); 
stopwatch.Stop(); 
Console.WriteLine($"C# işlem süresi: {stopwatch.Elapsed.TotalSeconds} saniye"); 
} 
} Merhaba MIS, algoritma ve programlama dersi başladı 
C# işlem süresi: 0.0131462 saniye 
 
 
 
package main 
import ( 
"fmt" 
"time" 
) 
func main() { 
start := time.Now() 
fmt.Println("Merhaba MIS, algoritma ve programlama") 
elapsed := time.Since(start) 
fmt.Printf("Go işlem süresi: %s saniye\n", elapsed) 
} 
Merhaba MIS, algoritma ve programlama 
Go işlem süresi: 87.37�s saniye 
 
 
use std::time::Instant; 
fn main() { 
let start = Instant::now(); 
println!("Merhaba MIS, algoritma ve programlama"); 
let duration = start.elapsed(); 
println!("Rust işlem süresi: {:?}", duration); 
}  
Merhaba MIS, algoritma ve programlama 
Rust işlem süresi: 22.044µs 
 
 
;use Time::HiRes qw(time); 
my $start = time(); 
print "Merhaba MIS, algoritma ve programlama\n"; 
my $end = time(); 
printf "Perl işlem süresi: %f saniye\n", $end - $start; 
Merhaba MIS, algoritma ve programlama   Perl işlem s�resi: 0.000011 saniye 

import time 
start = time.time() 
print("Merhaba MIS, algoritma ve programlama dersi başladı") 
end = time.time() 
print(f"Python işlem süresi: {end - start} saniye") 

Merhaba MIS, algoritma ve programlama dersi başladı 
Python işlem süresi: 5.4836273193359375e-06 saniye 
 

 
start = Time.now 
puts "Merhaba MIS, algoritma ve programlama" 
finish = Time.now 
puts "Ruby işlem süresi: #{finish - start} saniye" 
Hello World 
Merhaba MIS, algoritma ve programlama 
Ruby işlem süresi: 4.16e-06 saniye 

