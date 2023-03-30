## 자바로 백준 풀기
- 백준으로 자바 연습문제 풀면서 부족한 기본 개념정리
## 입력받기
scanner vs BufferReader 

```java
import java.io.*;
main() throws IOExeption{
    BufferReader bf = new BufferReader(new InputStreamReader(System.in));
    int input = Integer.parseInt(bf.readLine());// 정수 입출력
    String s = bf.readLine();//문자열 입출력
    StringTokenizer st = new StringTokenizer(bf.readLine());//공백까지 입력받기
    .
    .
    .
    bf.close();
}