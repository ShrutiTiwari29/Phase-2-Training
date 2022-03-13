create tables (for oracle specific query)
create table emp2(id number primary key,name varchar2(100),email varchar2(20),password varchar2(20),salary float,permission varchar2(20) default 'user' ); insert into emp2 values(100,'sharanya','sharanya987@gmail.com','sharanya',50000.0,'user'); insert into emp2 values(150,'snehal','snehal123@gmail.com','snehal',70000.0,'admin');
