# APOLLO – Modeling (CAD/FEA)

## 구조
- cad/       : CAD 원본(SLDPRT, STEP 등)
- fea/       : 해석 프로젝트
- exports/   : 렌더/중립포맷
- docs/

## Git LFS
리포 최초 설정 후:
```bash
git lfs install
git lfs track "*.step" "*.stp" "*.iges" "*.igs" "*.stl" "*.3mf" "*.sldprt" "*.sldasm" "*.f3d" "*.dwg" "*.dxf" "*.zip"
git add .gitattributes
git commit -m "chore: enable Git LFS for CAD/FEA"
```
