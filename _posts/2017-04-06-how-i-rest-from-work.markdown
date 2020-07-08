---
layout: post
title: 안드로이드 스튜디오 설치 및 설정
date: 2020-07-17 10:35:20 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: title_android.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Android, kotlin]
---
안드로이드 스튜디오 설치는 처음접하면 다소 까다롭고 복잡하지만 아래 포스팅 되어있는 순서들만 잘 따라하시면 쉽게 설치 하실 수 있습니다. 
구구절절 말씀드리면 보기 힘드실테니 딱! 엑기스만 뽑아서 포스팅 하겠습니다!
<br>
## STEP1. Java SDK 설치 방법
### STEP1-1. 안드로이드 스튜디오를 실행하려면  JAV SDK가 설치 되어 있어야 합니다. 아래 링크를 통해 JAVA SDK를 설치해주세요.
<br>

### <a class="se_og_box  __se_link" href="https://www.oracle.com/kr/java/technologies/javase-downloads.html" target="_blank" data-linktype="link" data-linkdata="{&quot;link&quot; : &quot;https://developer.android.com/studio/&quot;}">Java SE Development Kit 14 - Downloads</a>
> <div>Overview Downloads Documentation Community Technologies Training Java SE Development Kit 8 Downloads Thank you for downloading this release of the Java™ Platform, Standard Edition Development Kit (JDK™). The JDK is a development environment for building applications, applets, and compone</div>

<br>

### STEP1-2. Oracle JDK에서 JDK Download를 클릭합니다.
![download java sdk 1]({{site.url}}/assets/img/download-java-sdk.PNG)

### STEP1-3. 본인 PC에 맞는 환경을 찾아 다운로드 합니다.
![download java sdk 2]({{site.url}}/assets/img/download-java-sdk-2.PNG)

<br><br>
## STEP2. Android Studio 
### STEP2-1. JAVA SDK 설치가 완료 되셨다면 아래 링크를 통해 안드로이드 공식 사이트에 접속해주세요.
### <a class="se_og_box  __se_link" href="https://developer.android.com/studio/" target="_blank" data-linktype="link" data-linkdata="{&quot;link&quot; : &quot;https://developer.android.com/studio/&quot;}">Download Android Studio and SDK Tools &nbsp;|&nbsp; Android Developers </a>
> <div> Android Studio provides the fastest tools for building apps on every type of Android device. Download Not Available Your current device is not supported. See the system requirements . Download options Release notes Visual layout editor Create complex layouts with ConstraintLayout by adding constrain</div>

<br>
### STEP2-2. [DOWNLOAD ANDROID STUDIO] 버튼을 클릭합니다.
![download android 1]({{site.url}}/assets/img/download_android.PNG)

### STEP2-3. [DOWNLOAD ANDROID STUDIO] 버튼을 클릭하면 아래와 같은 창이 뜨는데 약관에 동의를 하시고 다운로드 버튼을 클릭하세요.
![download android 2]({{site.url}}/assets/img/download_android_2.PNG)

### STEP2-4. 다운로드가 완료되고 추가적인 설치를하면 아래와같은 창이 나오는데 [NEXT] 버튼 누르시면 됩니다.
![download android 3]({{site.url}}/assets/img/download_android_3.png)

### STEP2-5. 설치할 경로 확인하시고 NEXT!
![download android 4]({{site.url}}/assets/img/download_android_4.png)

### STEP2-6. [Do not import settings] 선택 후 [OK] 버튼을 클릭하세요!
![download android 5]({{site.url}}/assets/img/download_android_5.png)

### STEP2-7. [NETX] 버튼 클릭!
![download android 6]({{site.url}}/assets/img/download_android_6.png)

### STEP2-8. [Custom] 선택 후, [NETX] 버튼 클릭!
![download android 7]({{site.url}}/assets/img/download_android_7.png)


### STEP2-9. 원하시는 개발 테마를 선택한 뒤 [NEXT]클릭!!
### 저는 [Light] 테마로하면 눈의 피로감이 심해서 [Darcula]테마를 사용하였습니다. 대게 개발자들은 [Darcula] 테마 쓰더라구요.
![download android 8]({{site.url}}/assets/img/download_android_8.png)

### STEP2-10. 아래 이미지와 같이 Perfirnabce가 없을 수도 있습니다. 무시하시고 [NEXT] 버튼 클릭!!
![download android 9]({{site.url}}/assets/img/download_android_9.png)

### STEP2-11. 기본 설정값대로 냅두고 [NEXT] 버튼 클릭!!
![download android 10]({{site.url}}/assets/img/download_android_10.png)

### STEP2-12. 자!! 이제 모든 설정을 마쳤습니다![Finish]버튼을 클릭 후 완료 합니다!
![download android 11]({{site.url}}/assets/img/download_android_11.png)

<br><br>
## STEP3. 환경변수 설정
자! 여기까지 잘 따라 오셨나요?? 다 끝난줄 알았지만 마지막 단계가 있습니다. 
안드로이드 스튜디오를 설치후에 환경변수를 설정해주어야 안드로이드 스튜디오가 정상 작동합니다.
어렵지 않으니 천천히 따라오세요~^^

### STEP3-1. 윈도우 기준으로 [윈도우키 + R]을 누른후 [sysdm.cpl]을 입력해 해당 속성을 실행시킵니다.
![setting path 1]({{site.url}}/assets/img/setting_path_1.png)

### STEP3-2. [고급] 탭에서 오른쪽 하단에 [환경변수]를 클릭합니다.
![setting path 2]({{site.url}}/assets/img/setting_path_2.png)

### STEP3-3. [환경변수]를 클릭하면 아래와 같은 창이 뜰텐데 항목중에 변수에 있는 [Path] 항목을 선택 한 뒤 [편집]을 누릅니다.
![setting path 3]({{site.url}}/assets/img/setting_path_3.png)

### STEP3-4. 변수값의 맨 끝에 [;C:\Program Files\Android\Android Studio\jre\bin]를 입력하고 [확인]을 누릅니다.
### 경로 앞에있는 세미콜론(;)은 오타 아닙니다.꼭 넣어주세요!!
![setting path 4]({{site.url}}/assets/img/setting_path_4.png)

### STEP3-5. [확인]을 누르면 아래같이 나오는데 설치하시는 분들은 설정이 안되어 있을테니 새로만들기 버튼을 누르시면 됩니다!
![setting path 5]({{site.url}}/assets/img/setting_path_5.png)

### STEP3-6. 그러면 아래와 같이 환경 변수가 추가 되었음을 확인할 수 있습니다!
![setting path 7]({{site.url}}/assets/img/setting_path_7.png)

### STEP3-7. 이제 설정했던 환경변수를 한번 확인하시구 [확인] 버튼을 눌러 마무리합니다.
![setting path 8]({{site.url}}/assets/img/setting_path_8.png)

### 어때요? 생각보다 간단하죠?? 혹시 설치 도중 모르는것이 있다면 메일을 남겨주세요!
