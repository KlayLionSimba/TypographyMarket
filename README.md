### Smart Contract
https://gist.github.com/novela77/2bdc7522442975045064a0cf9fb3ab65

### React 앱 Github 레포지토리 
https://github.com/KlayLionSimba/TypographyMarket
 
### 4팀
심바_이종환(팀장), 이희진, 남현우, 이여원, 이민구
 
### 서비스 설명 

저희 팀은 타이포그래피 (폰트 및 캘리그래피)의 지적 재산권(IP)를 등록 하여 폰트 및 캘리그래피의 라이선스를 필요한
회사 및 단체가 그 라이선스를 구매 할수 있는 마켓과 마켓에서 발생한 수익을 분배하여 배당 할수 있는 DAO를 계획하고 있습니다.

클레이튼 블록체인과 KAS를 이용하여 블록체인을 통해 저작권을 구매 할수 있으며 KLAY NFT, FT등을 활용합니다 


타이포그래피 마켓 구성은 아래와 같습니다.

1. customer-front : 라이선스를 구매 할 사용자가 사용하는 페이지 , 라이선스를 구매 및 라이선스를 확인 할수 있습니다.
2. creator-front : 저작권가 사용하는 모바일 웹앱이며 , 파일 등록 및 라이선스 권리 설정을 할수 있습니다. 
3. service-backend: customer-front 와 creator-front 사용자들의 요청을 전달 받아 중개하는 역할을 합니다.


### Technology stack

- `Solidity`
- `React.js`
- `Node.js`
- `Kaikas`
- `IPFS`
- `KAS(Klaytn Application Service)`


#### 1. DAO (판매 수익에 대한 권리 NFT 발행) 
폰트 및 캘리그래프의 저작권자가 크리에이터 전용 페이지에서 저작권 파일을 등록 하여 2.라이선스 판매 마켓에서 발행한 수익금을 배당 받을수 있는 권리를 
가지는 1)NFT 토큰을 발행힙니다. 발행된 토큰은 오픈 마켓에서 거래될수 있으며 홀더에게는 라이선스 판매 마켓에서 발행한 수익을 DAO 트레져리로 부터 배당 받을수 있습니다.

#### 2.라이선스 마켓
creator는  폰트등의 라이선스 범위 및 기간을 선택하여 저작권을 1)판매 할수 있도록 하며
2)customer는 kaikas 통해 해당 아이템을 구매 할수 있으며

<img width="1441" alt="market_sample" src="https://user-images.githubusercontent.com/28801061/152287851-a19428d6-eda7-4202-93eb-9cb994d437dc.png">

3)구매한 저작권은 모바일 및 웹에서 라이선스 구매 여부를 확인 할수 있습니다. 

![license](https://user-images.githubusercontent.com/28801061/152295354-aba8fa2f-011d-4c49-ab8a-8af49b833e38.png)

  
감사합니다. 
