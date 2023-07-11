# 리엑션
이 기능은 이모지를 통해 다른 사용자의 노트에 반응을 쉽게 추가할 수 있게 해 줍니다.
Misskey Web에서 리엑션을 추가하려면, 노트의 + 아이콘을 눌러 선택기를 열어 선택할 수 있습니다.
반응에 [커스텀 이모지](./custom-emoji.md)를 이용할 수도 있습니다.

## 이모지 선택기 사용자 설정
Misskey Web에서능 이모지가 선택기에 표시되며, 순서와 크기를 변경할 수도 있습니다.
설정의 "리엑션" 탭에서 설정 가능합니다.

## 리모트 포스트에 리엑션
리엑션은 Misskey의 오리지널 기능입니다. 상대 인스턴스가 지원하지 않는 대부분의 상황에서는 "좋아요"로 전송됩니다.
보통 ActivityPub의 "좋아요"는 즐겨찾기로 구현되어 있습니다.

## 리모트 인스턴스에서의 리엑션
Misskey는 좋아요가 없기 때문에, 리모트 인스턴스의 "좋아요"는 '👍'로 표시됩니다.

:::tip
인스턴스 관리자가 '⭐' 리엑션으로 변경할 수도 있습니다.
관리자라면 [여기](../admin/default-reaction.md)를 확인해 주세요.
:::

## 리엑션 목록 보기
Misskey Web에서는, 프로필에서 "리엑션" 탭을 확인해 리엑션한 노트를 확인할 수 있습니다.
설정에서 이러한 목록을 공개로 설정할지 결정할 수도 있습니다.