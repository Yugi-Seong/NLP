# NLP

[1] 아나콘다 가상환경 생성 및 활성화 / 비활성화 
#### 1. 가상환경 추가

```CMD
> conda create -n test_envs python=3.6 anaconda 
```

‘conda create -n’ 이라는 명령어를 통해 가상환경을 추가할 수 있으며 바로 뒤에 원하는 가상환경 이름을 적는다.
이후 ‘python= x.x’ 을 통해 가상환경의 python version을 설정해줄 수 있다.



#### 2. 가상환경 목록 확인

```CMD
> conda info --envs
```

이후 다시 목록을 확인하면 test_envs라는 이름의 환경이 새로 추가된 것을 확인할 수 있다.



#### 3. 가상환경 활성화

```CMD
> conda activate test_envs
```

‘activate test_envs’와 같이 수행하면 해당 가상환경이 활성화가 되며,
원래 활성화 되어있던 (base)가 (test_envs)로 바뀌는 것을 확인할 수 있다.



#### 4. 가상환경 비활성화

```CMD
> conda deactivate
```

conda deactivate를 통해 현재 활성화 된 가상환경을 비활성화 시킨다.



#### 5. 가상환경 제거

```CMD
> conda env remove -n test_env
```

