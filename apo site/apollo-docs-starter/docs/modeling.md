# Modeling (CATIA)

CATIA 기반 파트/어셈/도면, 교환 포맷(STEP/IGES), FEA 연계 규칙을 정리합니다.

## 파일 구조(권장)
- `CAD/Parts`, `CAD/Assemblies`, `CAD/Drawings`, `CAD/Catalogs`, `CAD/Viz`
- `exports/` — STEP/IGES/STL/PDF
- `FEA/` — 해석 입력/요약 결과
- `templates/` — 도면 템플릿, 재질 테이블

## LFS 정책
- 네이티브(`*.CATPart`, `*.CATProduct`, `*.CATDrawing`, `*.CGR`)는 **Git LFS** 필수
- 공유는 `exports/`의 STEP/PDF 우선

## Repositories
- (예) apollo-modeling — `https://github.com/<org>/apollo-modeling`
