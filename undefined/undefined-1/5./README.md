# 5. 지속적 통합과 배포 자동화, 젠킨스

> docker builder → docker push → kubectl create → kubectl expose
>
> 이 4가지 과정을 통해 "새로 개발한 어플리케이션을 쿠버네티스에서 사용하는 과정" 이라 정의할 수 있다.
>
> 또한, 이러한 과정을 **파이프라인** 이라고 한다.

> 자동화 과정은 크게 지속적 통합(CI, Countinuous Integration), 지속적 배포(CD, Countinuous Deployment) 두 가지로 정의되며, 이 둘을 합쳐 CI/CD라고 칭한다.
