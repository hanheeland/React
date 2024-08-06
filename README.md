## 나만의 감정 일기장

- https://hanhee-diary-project.web.app/

- React Hook 사용
  -   React Hook 이란, 리액트 v16.8에 새로 도입된 기능으로, 함수형 컴포넌트(Functional Component)에서 사용되는 몇가지 기술들
  -   useState: 함수형 또는 클래스형 컴포넌트의 상태를 관리하고, 변경할 수 있도록 도와주는 하나의 React Hook. (보통 관리해야 할 State가 1개일 경우 사용)
  -   useEffect: React component가 랜더링 될 때마다 특정 작업을 실행할 수 있도록 하는 React Hook.
  -   useContext: context를 좀더 편하게 사용할 수 있도록 도와주는 React Hook. / 부모가 자식컴포넌트에게 일일이 props를 넘겨주지 않고도 컴포넌트 트리 전체에 데이터를 전달할 수 있게 해준다.
  -   useReducer: State(상태)를 관리하고 업데이트하는 Hook인 useState를 대체할 수 있는 Hook. / 한 컴포넌트 내에서 State를 업데이트하는 로직 부분 을그 컴포넌트로부터 분리시키는 것을 가능. (보통 관리해야 할 State가 1개 이상, 복수일 경우 사용)
  -   useRef: 저장공간 또는 DOM요소에 접근하기 위해 사용되는 React Hook. (불필요한 재렌더링을 하지 않는다는 장점)
  -   useCallback: React component에서 함수를 메미이제이션하여 성능을 최적화하는 데 사용되는 React Hook. (특정 함수를 새로 만들지 않고 재사용하고 싶을때 사용)
  -   useMemo: React component에서 계산 비용이 큰 연산을 최적화하는 데 사용되는 React Hook. (함수형 컴포넌트에서만 사용 가능 / 특정 결과값을 재사용 할 때 사용)
- React.memo: 함수 컴포넌트 최적화를 돕는 고차원 함수 (클래스형, 함수형 컴포넌트 모두 사용 가능)
- 사용기술: React, Firebase, localStorage
