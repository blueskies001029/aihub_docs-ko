---
icon: chevron-right

order: 1000
---

``Last update: Mar 7, 2024``
***
###### ‎ 
:::content-center
## 요구 사항

##### ``계속 진행하기 전에 다음 요구 사항을 충족하는지 확인하세요.``
:::
###### ‎
||| <u> 요구 사항 </u>
- 모델의 <u>[**.PTH**](https://docs.aihub.wtf/essentials/voice-models/#voice-model-files)</u> 파일.        
- 모델의 <u>[**.INDEX**](https://docs.aihub.wtf/essentials/voice-models/#voice-model-files)</u> 파일.      
- 모델에 대한 일반적인 정보.
- 학습 과정에 대한 일반적인 정보.     
- 허깅페이스 계정   
- 모델의 **<u>MR이 없는</u>** 오디오 샘플 1개 이상.       
|||
:::


:::content-center
###### ‎ 
##  피해야 할 사항 :icon-x:
##### ``이 경우 게시물의 자격이 박탈될 수 있습니다.``
:::
‎
:   ‎
:::
#### :icon-chevron-right: 파일이 올바르지 않음
- .ZIP 파일은 **올바른** `.INDEX` & `.PTH` 파일을 전부 포함해야 합니다. 자세한 사항은 <u>[여기](https://docs.aihub.wtf/essentials/voice-models/#voice-model-files)</u> 에서 확인하세요.
***
###### ‎ 
#### :icon-chevron-right: 모델 품질이 낮음.
- <u>**나쁜 모델은 이렇습니다:**</u>       

   - 긁힘/삐걱거림.
   - 막힌 듯한 소리.
   - 원본과 닮지 않음.
   - 특정 음을 도달할 수 없음.
   - 어눌한 말투.
   - 의도한 언어로 단어를 올바르게 발음할 수 없음.
   - <u>[아티팩트](https://docs.aihub.wtf/rvc/resources/artifacting/)</u> 가 있음.
***
###### ‎ 
#### :icon-chevron-right: 구형 추출 방법이 사용됨.
{.list-icon}
- :icon-check-circle: 오직 **Mangio-Crepe** 또는 **RMVPE** 만 허용됩니다. 자세한 내용은 <u>[여기](https://docs.aihub.wtf/rvc/resources/inference-settings/#pitch-extraction-algorithm)</u>

- :icon-x-circle: Harvest, Dio, Crepe-Tiny, PM, etc. 은 사용되지 않습니다.

***
###### ‎ 
#### :icon-chevron-right: 오디오 샘플에 MR이 존재함
- 저작권이 없는 음악이라도 오디오 데모에 **어떤** 음악도 포함하지 마세요. 그 이유는 다음과 같습니다:
  
     - 저작권에 대한 우려.
     - 많은 경우 음악이 음성 모델의 결함을 "숨겨서" 모델의 품질을 판단하기 어렵게 만들 수 있습니다.
***
#### :icon-chevron-right: 오디오 데모가 수정됨.
- 데모에 리버브를 추가하거나 EQ를 적용하거나 어떤 식으로든 변경하면 모델을 충실하게 표현할 수 없으므로 데모를 변경하지 마세요. RVC의 수정되지 않은 원본 출력이어야 합니다.

- 오디오의 시작/끝 부분의 무음 자르기는 유효합니다. :icon-check-circle: 
###### ‎  
***
###### ‎
:::content-center
## 단계
‎
:   ‎
:::
#### Step 1: 모델 압축
- **.PTH** 와 **.INDEX** 파일을 합쳐 ``.ZIP`` 파일로 <u>[압축</u>](https://support.microsoft.com/en-us/windows/zip-and-unzip-files-8d28fa72-f2f9-712f-67df-f80cf89fd4e5) 합니다..
         
- .7ZIP이나 .RAR 이 아닌 **.ZIP** 파일이어야 합니다.
***
###### ‎
#### Step 2: 업로드
- ZIP 파일은 허깅페이스의 `openrail` 라이선스의 **public** 리포지토리에 저장해야 합니다.     

- <u>[여기</u>](https://docs.aihub.wtf/essentials/voice-models/#uploading-to-hugging-face) 에서 방법을 알아보십시오.
***
###### ‎
#### Step 3: 제출물 준비
- 모델이 준비되면 **#get-model-maker** 채널로 이동합니다.  

- QCBot**의 `/submit` 명령을 입력한 후 명령을 클릭합니다.      

<img src="../modelmaker-img/submit.png" alt="image" width="600" height="auto">‎               
‎     
:::content-center
#### ``이제 모델에 대한 정보를 입력하세요.:``  
:::

**modelname**
:     모델의 이름입니다.   

**rvc**
:     학습된 RVC 버전(거의 항상 v2입니다).

**extraction**
:     사용된 <u>[추출 방식](https://docs.aihub.wtf/rvc/resources/inference-settings/#pitch-extraction-algorithm)</u> 입니다.

**epochs**
:     총 <u>[에포크](https://docs.aihub.wtf/rvc/resources/epochs--tensorboard/)</u> 양입니다.

**link**
:     모델의 허깅 페이스의 다운로드 링크입니다.

**image**
:     모델을 나타내는 이미지(사람/캐릭터)를 입력합니다.     

**demo**
:     말하거나 노래하는 오디오 샘플.

**note** 
:   선택 사항입니다. 원하는 경우 모델에 대한 더 많은 설명을 추가합니다.

***
!!!success 
``#voice-models``에 모델을 다시 게시할 때 더 많은 샘플을 첨부할 수 있습니다.
!!!
***
###### ‎
#### Step 4: 제출물 보내기
- 정보 입력이 완료되면 메시지를 보냅니다.       

- 모든 것이 정상적으로 진행되면 제출물이 대기열에 추가되고 봇이 **submission ID**가 포함된 확인 메시지를 보냅니다.     
<u>**ID가 있으면:**</u>        
   - 대기열에 있는 제출물의 순서를 확인하려면 ``/queue`` 명령 뒤에 ID를 입력합니다. (예: ``/queue 251``).        
   - ``/cancel`` 명령 뒤에 ID를 입력해 제출을 취소합니다.    
‎     
- 이제 **Model QC**(품질 검사자)가 모델을 확인할 때까지 기다리세요. 검토가 완료되면 알림을 받게 됩니다.    

- 모델이 승인되면 봇이 다음과 같은 내용으로 알려줍니다:  

   <img src="../modelmaker-img/approved.png" alt="image" width="" height="auto">‎     
‎    
- 그런 다음 해당 모델(및 향후 모델)을 ``#voice-models`` 포럼에 다시 게시할 수 있습니다.

***
###### ‎
:::content-center
#### `You have reached the end.`

[!badge variant="info" size="xl" corners="pill" icon="paper-airplane" iconAlign="right" text="Report Issues"](https://docs.aihub.wtf/rvc/#contributions)
:::
