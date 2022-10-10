---
description: How to install the plugin
---

# ⚙ 처음 설치 방법

{% hint style="info" %}
당신은 **실수**와 많은 재시작을 피하기 위해 **반드시** 이 초기 설정을 당신의 **테스트 서버**에서 진행하는 것을 추천합니다. 플레이어들은 서버가 오프라인 상태인 것을 좋아하지 않습니다.\
이 과정을 마무리 했다면, 당신은 파일들을 당신의 실제 서버에 업로드 할 수 있습니다.
{% endhint %}

{% hint style="danger" %}
당신은 첫 번째뿐만 아니라 **반드시** 모든 설치 과정을 완료하여야 합니다.
{% endhint %}

## 첫 번째 - 플러그인과 API들을 설치하세요

- [**ProtocolLib**](https://www.spigotmc.org/resources/protocollib.1997/) 설치
- [**LoneLibs**](https://www.spigotmc.org/resources/lonelibs.75974/) 설치
- (선택) **LightAPI** ([1.14, 1.15, 1.16](http://a.devs.beer/lightapi-old) | [1.17, 1.18](http://a.devs.beer/lightapi-new)) 설치
- (선택) [**Lib's Disguises**](https://www.spigotmc.org/resources/libs-disguises-free.81/) 커스텀 몹을 만들 계획이 있다면 설치하세요.
- **ItemsAdder.jar** 파일을 당신의 plugins 폴더에 추가하세요.
- 서버를 시작하세요.
- ItemsAdder 플러그인이 **모든 것**을 불러오게 하세요.

첫 과정이 마무리 되었습니다.\
이제 당신은 리소스팩을 설정하기 위해 **두 번째** 과정을 꼭 마무리해야 합니다. (걱정하지 마세요, 그다지 어렵지 않습니다.)

## 두 번째 - 리소스팩 첫 설치

#### 리소스팩을 호스팅할 방법을 결정하세요:

{% content-ref url="plugin-usage/resourcepack-hosting/" %}
[resourcepack-hosting](plugin-usage/resourcepack-hosting/)
{% endcontent-ref %}

## 선택 과정

### ItemsAdder 플러그인의 공식적인 커스텀 컨텐츠를 추가하세요

![](.gitbook/assets/items_showcase_gif.apng)

**ItemsAdder**에는 이미 만들어진 많은 커스텀 컨텐츠가 포함되어 있습니다.\
이 컨텐츠들은 플러그인을 다운로드 한다고 자동적으로 적용되지 않는데, 왜냐하면 몇몇 사람들이 모든 아이템이나 특성들이 자동적으로 그들의 서버에 추가되는 것을 원치 않을 수 있기 때문입니다.

#### 기본 팩

![](<.gitbook/assets/image (47).png>)

- [여기](https://github.com/ItemsAdder/DefaultPack/releases/latest)&#x20;에서 최신 버전의 기본 팩을 다운로드 하세요.
- 해당 팩의 압축을 **ItemAdder** 폴더에 풀고 덮어쓰세요.
- 서버 내에서 `/iazip` 커맨드를 실행하세요. (그리고 당신의 리소스팩을 **스스로 호스팅**하지 않는다면, [호스팅 방법](plugin-usage/resourcepack-hosting/) 절차를 따라주세요.)

#### 추가 팩 (선택)

![](<.gitbook/assets/image (50).png>)

- 당신이 만약 기본 팩 말고도 다른 팩을 원한다면 [여기](https://github.com/ItemsAdder/OtherPacks/releases/latest)에서 더 많은 컨텐츠를 추가하는 추가 팩을 다운로드 하세요.
- 해당 팩의 압축을 **ItemAdder** 폴더에 풀고 덮어쓰세요.
- 서버 내에서 `/iazip` 커맨드를 실행하세요. (그리고 당신의 리소스팩을 **스스로 호스팅**하지 않는다면, [호스팅 방법](plugin-usage/resourcepack-hosting/) 절차를 따라주세요.)

If you're on 1.17 or lower you have to change the ores generation:

* Open these files and set `enabled: true`.\
  `ItemsAdder\data\items_packs\iaalchemy\worlds_populators_old.yml`\
  `ItemsAdder\data\items_packs\iasurvival\ores\worlds_populators_old.yml`
* Open these files and set `enabled: false`.\
  `ItemsAdder\data\items_packs\iaalchemy\worlds_populators_1_18.yml`\
  `ItemsAdder\data\items_packs\iasurvival\ores\worlds_populators_1_18.yml`

### Removing default items

{% content-ref url="faq/removing-default-stuff/" %}
[removing-default-stuff](faq/removing-default-stuff/)
{% endcontent-ref %}

### Avoid glitched blocks

{% content-ref url="faq/blocks-minerals-issues/custom-blocks-glitch-texture/avoid-glitched-blocks.md" %}
[avoid-glitched-blocks.md](faq/blocks-minerals-issues/custom-blocks-glitch-texture/avoid-glitched-blocks.md)
{% endcontent-ref %}
