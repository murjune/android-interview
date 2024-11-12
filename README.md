# android-interview

매주 하나의 주제를 통해 모의 면접을 진행하는 스터디

## 스터디 주제
- 1주차: JAVA
- 2주차: Kotlin
- 미정: Android, OOP/Architecture, Coroutine/Flow, CS

## 스터디 방식
그 주차 스터디 주제를 바탕으로 면접자 2명, 피면접자 1명, 관찰자 1명으로 모의 면접 진행한다.

- 20~30분 질문
- 10분 피드백
- 2명 끝나면 휴식

## 규칙

1. 스터디 시간을 엄수한다.(지각 시 5000원 벌금)
2. 질문 답변 최소 12개 이상 작성해온다.(못해오면 1개당 1000원 벌금)

> 규칙 불이행시 이 레포지토리에 박제된다.

## 면접 질문지

 <details>
  <summary> <h2> Java </h2></summary>

## 접근 제어자, 클래스 및 키워드

- [접근 제어자의 차이점](https://github.com/murjune/android-interview/discussions/36)
- 인터페이스와 추상 클래스의 차이
- [static과 non-static의 차이](https://github.com/murjune/android-interview/discussions/21)
- final 키워드에 대해 설명

## String 및 관련 메모리 관리

- [String Pool이 무엇이고 사용하는 이유](https://github.com/murjune/android-interview/discussions/6)
- [equals와 hashCode를 사용하는 이유](https://github.com/murjune/android-interview/discussions/10)
- [String, StringBuffer, StringBuilder의 차이](https://github.com/murjune/android-interview/discussions/9)

## Java 파일 및 실행 과정

- [Java 파일이 실행되는 과정](https://github.com/murjune/android-interview/discussions/19)
- Optional에 대한 설명과 사용 시 주의사항
- try-with-resources에 대해 설명

## Objects vs Primitives

- [String 클래스는 어떻게 구현되나요? 왜 불변으로 만들었나요?](https://github.com/murjune/android-interview/discussions/7)
- [String이 불변이라는 것은 무엇을 의미하나요?](https://github.com/murjune/android-interview/discussions/8)
- Integer vs int
- [Call by Value vs Call by Reference](https://github.com/murjune/android-interview/discussions/26)

## 객체 비교와 복사

- [동등성과 동일성의 차이](https://github.com/murjune/android-interview/discussions/35)
- 깊은 복사(deep copy)와 얕은 복사(shallow copy)에 대해 설명

## 함수 및 표현식

- [익명함수와 람다 표현식에 대해 설명](https://github.com/murjune/android-interview/discussions/31)
- 함수형 인터페이스(Functional Interface)란
- 제네릭이란

## 클래스 및 객체 관리

- [Reflection에 대한 설명과 장단점](https://github.com/murjune/android-interview/discussions/32)
- [Enum의 장단점](https://github.com/murjune/android-interview/discussions/18)
- Wrapper Class, Boxing, Unboxing 차이

## 메서드 및 키워드

- 오버로딩과 오버라이딩의 차이
- [synchronized 키워드에 대해 설명](https://github.com/murjune/android-interview/discussions/20)

## 직렬화 및 역직렬화

- [직렬화와 역직렬화이 무엇이고, 언제 사용하는가?](https://github.com/murjune/android-interview/discussions/34)
- [transient 란?](https://github.com/murjune/android-interview/discussions/33)

## 컬렉션 프레임워크 및 자료구조

- [Iterator & Collection & Stream](https://github.com/murjune/android-interview/discussions/13)
- [Stack 대신 Deque를 사용하는 이유](https://github.com/murjune/android-interview/discussions/28)
- [ArrayList와 LinkedList의 차이](https://github.com/murjune/android-interview/discussions/37)
- Set과 List의 차이
- [Arrays Vs ArrayLists](https://github.com/murjune/android-interview/discussions/1)
- HashSet Vs TreeSet
- HashMap Vs Set
- [HashMap Vs HashSet](https://github.com/murjune/android-interview/discussions/27)
- [컬렉션 프레임워크란 (Kotlin Collection과 비교)](https://github.com/murjune/android-interview/discussions/11)
- [for문 vs Stream vs Sequence](https://github.com/murjune/android-interview/discussions/22)
- [Java Stream API란 (Kotlin Sequence와 차이)](https://github.com/murjune/android-interview/discussions/30)

## JVM & 가비지 컬렉션

- [JVM 메모리 영역에 대해 설명](https://github.com/murjune/android-interview/discussions/16)
- [가비지 컬렉션이란](https://github.com/murjune/android-interview/discussions/15)
- [가비지 컬렉션는 언제 일어나는가?](https://github.com/murjune/android-interview/discussions/14)
- [JVM 동작 원리를 설명해주세요.](https://github.com/murjune/android-interview/discussions/5)
  
</details> 

<details>
  <summary> <h2> Kotlin </h2></summary>

  # 1. 기초 문법 및 키워드
- [코틀린의 장점](https://github.com/murjune/android-interview/discussions/39)
- [코틀린이 실행되는 과정 설명](https://github.com/murjune/android-interview/discussions/58)
- [Property 란?](https://github.com/murjune/android-interview/discussions/60)
- [Field vs Property](https://github.com/murjune/android-interview/discussions/75)
- [Kotlin에서 const를 사용하는 이점은?](https://github.com/murjune/android-interview/discussions/40)
- [Kotlin에서 lateinit vs by Lazy?](https://github.com/murjune/android-interview/discussions/41)
- [lateinit 변수가 초기화되었는지 확인하는 방법](https://github.com/murjune/android-interview/discussions/42)
- [Kotlin에서 init 블록이란?](https://github.com/murjune/android-interview/discussions/59)
- [val과 var의 차이점은?](https://github.com/murjune/android-interview/discussions/61)
- [Generic이란?](https://github.com/murjune/android-interview/discussions/43)
- [Generic 타입 상한 제한(upper bound)이란?](https://github.com/murjune/android-interview/discussions/68)
- [Generic 변성에 대해 설명하시오](https://github.com/murjune/android-interview/discussions/69)
- [Star Projection 이란?](https://github.com/murjune/android-interview/discussions/70)
- [Kotlin에서 inline 함수란?](https://github.com/murjune/android-interview/discussions/44)
- [Kotlin에서 reified 키워드란?](https://github.com/murjune/android-interview/discussions/45)
- [backing property 설명해주세요.](https://github.com/murjune/android-interview/discussions/46)
- [noinline이란?](https://github.com/murjune/android-interview/discussions/47)
- [crossinline이란?](https://github.com/murjune/android-interview/discussions/48)
- [open 키워드란?](https://github.com/murjune/android-interview/discussions/57)
- [Kotlin 접근 제어자](https://github.com/murjune/android-interview/discussions/62)
- [infix 키워드란?](https://github.com/murjune/android-interview/discussions/54)
- Kotlin의 Lable이란?
- [일급 시민이란?](https://github.com/murjune/android-interview/discussions/49)
- [타입 변환(Type Conversion) vs 타입 캐스팅(Type Casting)](https://github.com/murjune/android-interview/discussions/63)

# 2. 클래스 및 객체 지향 프로그래밍
- [companion object란?](https://github.com/murjune/android-interview/discussions/50)
- Kotlin에서 싱글톤 클래스를 생성하는 방법
- [Kotlin에서 데이터 클래스란?](https://github.com/murjune/android-interview/discussions/71)
- [Kotlin에서 Java의 정적 메서드에 해당하는 것은?](https://github.com/murjune/android-interview/discussions/65)
- [Kotlin의 sealed class를 언제 사용하나요?](https://github.com/murjune/android-interview/discussions/52)
- [Kotlin의 JvmStatic 어노테이션이란?](https://github.com/murjune/android-interview/discussions/55)
- [Kotlin의 JvmField 어노테이션이란?](https://github.com/murjune/android-interview/discussions/56)
- [Kotlin의 JvmOverloads 어노테이션이란?](https://github.com/murjune/android-interview/discussions/64)
- Kotlin의 inline/value 클래스 설명
- [Kotlin에서 open과 public의 차이점은?](https://github.com/murjune/android-interview/discussions/57)

# 3. 함수와 람다
- [Kotlin에서 고차 함수란?](https://github.com/murjune/android-interview/discussions/66)
- [Kotlin에서 람다식이란?](https://github.com/murjune/android-interview/discussions/67)
- [Kotlin에서 let, run, with, also, apply의 설명 및 사용 사례](https://github.com/murjune/android-interview/discussions/51)
- apply와 with를 선택하는 방법

</details>

<details>
  <summary> <h2> Android </h2></summary>

### 공통 개발자 기술 질문

	1.	PNG와 JPG의 차이점은?
	2.	Dynamic Programming이란?
	3.	Virtual Memory란?
	4.	Garbage Collection이란?
	5.	Cache란?
	6.	Database Index 추가의 장단점은?
	7.	비대칭 암호화란?
	8.	HDD, SSD, DRAM 각각의 성능은?
	9.	GIT의 장점은?

### Android 개발자 기술 질문

	1.	DIP(Dependency Inversion Principle)란?
	2.	ConstraintLayout의 장점은?
	3.	Activity 생명 주기는?
	4.	WeakReference란?
	5.	Parcelable이란?
	6.	고해상도 이미지의 로딩 방법은?
	7.	Looper란?
	8.	MultiDex란?
	9.	Proguard의 원리는?

### 자료구조 및 알고리즘

	1.	List와 Set의 차이
	2.	List.distinct()를 사용하는 것과 Set 사용하는 것의 차이
	3.	ArrayList와 LinkedList의 차이
	4.	여러 스레드에서 공유 자원 접근 시 주의 사항
	5.	동시성 문제를 겪은 경험이 있는가?
	6.	동기화하는 방법?
	7.	synchronized를 메소드 블록과 내부 블록에서 사용하는 것의 차이
	8.	싱글톤을 사용한 경험과 동시성 문제

### Kotlin 언어 및 클래스 사용

	1.	data class를 사용하면 자동으로 오버라이드 되는 메서드들
	2.	Enum class를 사용한 경험이 있는가?
	3.	Enum class 대신 sealed class와 object를 사용할 수 있는데, 언제 Enum class를 사용해야 하는가?

### 네트워크 및 에러 처리

	1.	네트워크 에러 처리 관련 경험
	2.	코루틴 사용 시 예외 처리 방법

### Android 기초

	1.	Android 앱이 왜 느려질 수 있는가?
	2.	Context란 무엇이며, 어떻게 사용되는가?
	3.	Android 애플리케이션의 구성 요소
	4.	Android 애플리케이션의 프로젝트 구조
	5.	AndroidManifest.xml이란 무엇인가?
	6.	Application 클래스란 무엇이며, 역할은 무엇인가?
	7. Android 4대 컴포넌트는 무엇인가요
	8. 다국어 지원은 어떻게 하나요


### Activity와 Fragment

	1.	Fragment를 생성할 때 기본 생성자를 사용하는 것이 왜 권장되는가?
	2.	Activity 생명주기
	3.	onCreate()와 onStart()의 차이점
	4.	onPause()와 onStop() 없이 onDestroy가 호출될 수 있는 경우
	5.	setContentView()를 onCreate()에서 호출하는 이유
	6.	onSaveInstanceState()와 onRestoreInstanceState()의 역할
	7.	Fragment 생명주기
	8.	launchMode란 무엇인가?
	9.	Fragment와 Activity의 차이점 및 관계
	10.	Fragment와 Activity 중 어느 경우에 Fragment를 사용하는가?
	11.	FragmentPagerAdapter와 FragmentStatePagerAdapter의 차이점
	12.	Backstack에서 Fragment를 추가 및 교체할 때 차이점
	13.	Fragment 간의 통신 방법
	14.	Retained Fragment란?
	15.	Fragment 트랜잭션에서 addToBackStack()의 목적


### View와 ViewGroup

	1.	View란 무엇인가?
	2.	View.GONE과 View.INVISIBLE의 차이점
	3.	커스텀 뷰 생성 방법
	4.	ViewGroup이란 무엇이며, View와 어떻게 다른가?
	5.	Canvas란?
	6.	SurfaceView란?
	7.	Relative Layout과 Linear Layout의 차이
	8.	ConstraintLayout이란?
	9.	View 트리란 무엇이며, 깊이를 최적화하는 방법
	10. inflate에 대해 설명해주세요

### RecyclerView 및 리스트

	1.	ListView와 RecyclerView의 차이점
	2.	RecyclerView의 내부 동작
	3.	RecyclerView 성능 최적화 방법
	4.	Nested RecyclerView 최적화 방법
	5.	RecyclerView가 ListView보다 성능이 우수한 이유
	6.	RecyclerView의 구성 요소
	7.	RecyclerView.Adapter 및 RecyclerView.ViewHolder의 역할
	8.	LayoutManager란?
	9.	단일 RecyclerView에서 여러 뷰 유형을 처리하는 방법
	10.	DiffUtil과 RecyclerView 성능 개선
	11.	RecyclerView.setHasFixedSize(true)의 목적
	12.	RecyclerView에서 특정 항목을 업데이트하는 방법
	13.	SnapHelper란 무엇인가?

### Dialog와 Toast

	1.	Dialog란?
	2.	Toast란?
	3.	Dialog와 Dialog Fragment의 차이점

### 인텐트 및 브로드캐스트

	1.	Intent란?
	2.	암시적(Implicit) Intent란?
	3.	명시적(Explicit) Intent란?
	4.	BroadcastReceiver란?
	5.	Sticky Intent란?
	6.	브로드캐스트와 인텐트를 통해 앱에서 메시지를 전달하는 방법
	7.	PendingIntent란?
	8.	브로드캐스트의 유형
	9. Intent 필터

### 서비스

	1.	Service란?
	2.	Service와 IntentService의 차이점
	3.	Foreground Service란?
	4.	JobScheduler란?
	5. Background Service란?

### 프로세스 간 통신

	1.	두 개의 별도 Android 앱 간의 상호작용 방법
	2.	Android 앱을 여러 프로세스에서 실행할 수 있는지 여부와 방법
	3.	AIDL이란? 바운드 서비스 생성 시 AIDL 사용 단계
	4.	Android에서 백그라운드 처리 방법
	5.	ContentProvider의 역할과 일반적인 용도

### 장기 작업

	1.	병렬 작업 실행 및 완료 시 콜백 받기
	2.	ANR이란? ANR 방지 방법
	3.	AsyncTask(Deprecated)란?
	4.	AsyncTask 사용 시 문제점
	5.	데몬 스레드와 사용자 스레드의 차이
	6.	Looper, Handler, 및 HandlerThread 설명
	7.	Android 메모리 누수와 가비지 컬렉션

### 멀티미디어 콘텐츠

	1.	Bitmap 처리 방법
	2.	Bitmap 풀 사용 방법
	3. Android에서 사이즈가 큰 이미지를 불러올려고 합니다. 어떻게 해야할까요?

### 데이터 저장 및 관리

	1.	Jetpack DataStore Preferences
	2.	Android 앱에서 데이터 유지 방법
	3.	ORM이란? 작동 원리
	4.	화면 회전 시 Activity 상태 보존 방법
	5.	Android 앱의 데이터 저장 방식
	6.	Scoped Storage 설명
	7.	데이터 암호화 방법
	8.	SharedPreferences의 commit()과 apply() 차이

### UI 및 시각적 표현

	1.	Spannable이란?
	2.	SpannableString이란?
	3.	Android에서 텍스트 사용 시 모범 사례
	4.	다크 모드 구현 방법

### 메모리 최적화

	1.	onTrimMemory() 메서드
	2.	OutOfMemory 문제 해결 방법
	3.	Android 애플리케이션의 메모리 누수 확인 방법

### 배터리 최적화

	1.	배터리 사용량을 줄이는 방법
	2.	Doze 및 App Standby란?
	3.	Overdraw란?

#### 화면 크기 대응

	1.	다양한 해상도를 지원하는 방법
	2.  dp sp px 차이

### 권한 관리

	1.	권한 보호 수준과 종류

### 네이티브 프로그래밍

	1.	NDK란? 유용성
	2.	Renderscript란?

### Android 시스템 내부

	1.	Android Runtime이란?
	2.	Dalvik, ART, JIT, AOT의 차이
	3.	DEX란?
	4.	Multidex란?
	5.	가비지 수집을 강제 호출할 수 있는지 여부

### Android Jetpack

	1.	Android Jetpack이란? 사용 이유
	2.	ViewModel이란? 유용성
	3.	Android 아키텍처 구성 요소 설명
	4.	LiveData란?
	5.	LiveData와 ObservableField의 차이점
	6.	setValue와 postValue의 차이점
	7.	Fragment 간 ViewModel 공유 방법
	8.	WorkManager와 사용 사례
	9.	ViewModel의 내부 작동 방식
 10. MVVM viewModel과 AAC viewModel 차이

### 기타

	1.	Serializable과 Parcelable의 차이
	2.	데이터 전달 시 Bundle 클래스를 사용하는 이유
	3.	앱 충돌 문제 해결 방법
	4.	Android 푸시 알림 시스템 설명
	5.	AAPT란?
	6.	FlatBuffers와 JSON 차이
	7.	HashMap, ArrayMap, SparseArray의 차이점
	8.	Annotation이란?
	9.	커스텀 Annotation 생성 방법
	10.	지원 라이브러리란? 도입 이유
	11.	Android Data Binding 설명
 12. apk와 aab 차이 설명
 13. Android 배포 프로세스에 대해 설명해주세요
 14. Kapt에 대해 설명해주세요

### Android 라이브러리

	1.	OkHttp Interceptor 설명
	2.	OkHttp HTTP 캐싱
	3.	의존성 주입 프레임워크(Dagger)를 사용하는 이유
	4.	Dagger의 작동 방식
	5.	Dagger 2와 Dagger-Hilt의 선택 기준
	6.	Dagger에서 Component란?
	7.	Dagger에서 Module이란?
	8.	RxJava에서 CompositeDisposable의 dispose와 clear 호출 시점
	9.	네트워킹에서 Multipart 요청을 처리하는 방법
	10.	Kotlin의 Flow란?
	11.	App Startup Library의 역할
	12.	RxJava란?
	13.	RxJava에서의 에러 처리 방법
	14.	FlatMap과 Map 연산자의 차이점
	15.	RxJava의 Create와 fromCallable 연산자의 사용 시점
	16.	RxJava의 defer 연산자의 사용 시점
	17.	RxJava에서 Timer, Delay, Interval 연산자의 사용 방법
	18.	RxJava에서 두 개의 네트워크 호출을 병렬로 수행하는 방법
	19.	Concat과 Merge 연산자의 차이
	20.	RxJava에서 Subject란?
	21.	RxJava의 Observable 유형과 사용 시점
	22.	RxJava를 사용한 검색 기능 구현 방법
	23.	RxJava 연산자를 사용한 RecyclerView의 페이지네이션
	24.	Android 이미지 로딩 라이브러리인 Glide와 Fresco, Piccaso, Coil의 작동 방식
	25.	RxJava에서 Schedulers.io()와 Schedulers.computation()의 차이점 26.	직렬화 라이브러리 Kotlinx-Serialization, Gson, Moshi의 차이점


### Android Architecture
 	1. MVVM 설명
 	2. MVI
 	3. MVC vs MVP vs MVVM vs MVI 아키텍처
	4. 클린 아키텍처란 무엇인가요?
 	4. 소프트웨어 아키텍처와 소프트웨어 설계의 차이점
 	5. Repository 패턴
 	6. 구글 권장 아키텍처 vs 클린 아키텍처
 	7. UDF

</details>
