# Pascal-Menghitung_Deret
program Bilangan;
uses crt;
var
  bila, bilb, bilsem, deret, i: integer;
begin
   write('Masukkan Jumlah Deret   : '); readln(deret);
   bila    := 0;
   bilb    :=1;
   bilsem  := 0;
   for i := 1 to deret do
   begin
   bilsem := bila + bilb;
   bila   := bilb;
   bilb  := bilsem;
   write(' ', bila,' ');
  end;
  Readkey;
  write('Setiap Kesulitan Pasti Ada Kemudahan Yang Di Berikan Oleh ALLAH SWT!!!');
  readln;
end.
