### 구현해야 할 것

1. useInput 에는 들어오는 값을 검증하는 코드가 빠져있습니다.
+ useInput에서 입력값을 검증할 수 있는 기능을 추가해주세요.
  -  `InputProps`, `useInput`의 props인 `validate` 를 주석해제하고, 아래와 같이 min, max 검증 함수의 Array를 입력으로 받도록 구현해주세요. `min(5)` 는 최소 5자 이상, `max(10)`는 최대 10자 이하입니다.
  ```jsx
  <TextField
    ...
    validate={[min(5), max(10)]}
    />
  ```
+ 만약 입력값에 문제가 있다면 에러를 출력할 수 있도록 구현해주세요.
+ 에러가 있을 때 '제출' 버튼을 클릭하면 제출이 되지 않도록 구현해주세요.

2. `TextField` 외 `CheckboxField`, `SelectboxField`를 추가해주세요.
3. `SimpleForm`, `TextField` 두 개의 컴포넌트에 대해서 https://github.com/testing-library/react-testing-library 의 패키지를 이용해서 테스트 코드를 작성해주세요.
# form-practice2
