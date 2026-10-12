# taskstonebar-steam-icons

Steam Inventory Service ItemDef 아이콘 호스팅 (`icon_url` / `icon_url_large`).
Valve 가 이 공개 URL 에서 내려받아 자기 서버에 캐시한다.

- 생성 원본: `kernys/taskstonebar` 모노리포 `harness/tools/taskstonebar_steam_icons.py`
  (`prepare_taskstonebar_steam.py --itemdefs-only` 가 `steam/icons/` 로 만든다).
- 파일 이름 = 원본 PNG 내용 해시. `<hash>.png` 256px, `<hash>_large.png` 1024px.
  그림이 바뀌면 이름도 바뀌므로 기존 파일은 지우지 않고 추가만 한다.
- Base URL: `https://raw.githubusercontent.com/kernys/taskstonebar-steam-icons/main/icons`
  (모노리포 game-profile `steam_inventory.icons.base_url`).
