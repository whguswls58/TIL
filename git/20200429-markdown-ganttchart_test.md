### markdown 그래프 테스트
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### markdown 간트차트 테스트
```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2014-01-01, 30d
    Another task     :after a1  , 20d
    section Another
    Task in sec      :2014-01-12  , 12d
    another task      : 24d
  ```

#### 문제
- VSCode상에서 mermaid 확장자를 이용해서 그래프와 간트차트를 그리는 것은 가능하나 이를 github에 올릴 경우에 확장자를 지원하지 않아 코드형식으로 출력됨
#### 문제 결론
   - GitHub은 공식적으로 github flavored markdown을 지원
   - 이 양식에 포함되지않은 것은 표현이 불가능
   - 소스는 남겨두고 깃헙에서는 png로 참조하는 방향으로 그래프를 추가하도록 한다.