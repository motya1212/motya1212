- var s,n,m,i,s1,s2:integer;
begin
readln(s);
readln(n);
s1:=0; s2:=0;
for i:=1 to n do
 begin
 readln(m);
 if s1+m<=s then s1:=s1+m else s2:=s2+m;
 end;
writeln(s1);
writeln(s2);
end.
