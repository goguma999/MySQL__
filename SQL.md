### 1.    
▪️ 사칙연산시 null값 의심! → **nvl 절대 고려**     
▪️ 문자 색시 대소문자 구분! -> **upper, lower**   
▪️ 날짜 다룰 땐 **to_date** 필수    

---------------------
### 2. nvl(숫자, 숫자), nvl(문자, 문자)     
형 통일하기 !!  

---------------------

### 3. 1=1       
```SQL
SELECT ename, sal, deptno
FROM EMP
WHERE 1=1
-- AND deptno = 10 OR deptno = 20 
   AND sal > 2000 ; 
```	

---------------------


