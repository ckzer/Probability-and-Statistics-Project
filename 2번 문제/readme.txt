모든 사진 파일은 첫 시행시의 결과값임.

ⓐ 모집단
모집단의 크기 100만 고정.
모집단의 크기를 100만으로 고정한 이유는 큰 모집단을 통해 통계적으로 안정된 분포를 얻기 위함

실행 결과

모집단의 크기가 커서 평균과 분산의 값이 어느정도 바뀌더라도, 형태가 크게 바뀌지 않았음.

ⓑ 초기 세팅값
초기 세팅값은 다음과 같음

과제에서 주어진 범위에서 실행한 경우
각각 크기가 10,30,61인 샘플을 뽑음

케이스 1 : 평균 50 표준편차 10
케이스 2 : 평균 100 표준편차 10
케이스 3 : 평균 50 표준편차 20

과제 범위 밖에서 실행한 경우
각각 크기가 1000, 10000, 100000인 샘플을 뽑음
케이스 4 : 평균 50 표준편차 10



실행 결과

랜덤 케이스를 계속해서 돌려본 결과,
10, 30, 61이 항상 확연한 차이를 보이지는 않았다. n이 충분히 크지 않아서 발생한 문제 같다.
10, 30이 61보다 모집단의 평균과 분산에 가까운 경우도 자주 보였다.
그래프로 시각화 한 결과를 보면 n이 10인 경우는 정규분포의 형태를 거의 따르지 않는 경우가 빈번함에도 대부분의 상황에서 평균과 분산은 모집단과 유사했다.
30과 61은 그래도 어느정도 정규분포 그래프와 비슷한 형태를 갖는 경우가 많았다. 

분산의 영향은 생각보다 더 컸다. 
분산이 작을수록 샘플의 평균과 분산이 모집단의 평균과 분산과 비슷했다.

따라서 n을 1000, 10000, 100000으로 늘려서 다시 실행해본 결과 항상 모집단과 유사한 평균과 분산을 가졌음.

샘플 크기가 작을 경우, 샘플의 분포가 모집단의 분포를 잘 따르지 않는 경우가 있지만 평균과 분산은 모집단과 유사한 경향을 보인다.
분산이 작을수록, 그리고 샘플 크기가 클수록 샘플의 평균과 분산이 모집단의 평균과 분산에 더 가깝게 나타난다.
샘플 크기를 크게 할수록 모집단과 유사한 통계적 특성을 가지게 된다