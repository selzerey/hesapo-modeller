# hesapo-modeller

hesapo.com'un tarayıcıda çalışan "Resim Arka Planı Silme" aracının model dosyaları. Derleme sırasında indirilir; depoda tutulmaz.

| Dosya | Kaynak | Lisans | Not |
|---|---|---|---|
| `birefnet-lite-fp16.bin` | [ZhengPeng7/BiRefNet](https://github.com/ZhengPeng7/BiRefNet) → [onnx-community/BiRefNet_lite-ONNX](https://huggingface.co/onnx-community/BiRefNet_lite-ONNX) `onnx/model_fp16.onnx` | MIT | 1024×1024, ImageNet normalizasyonu, WebGPU |
| `isnet-q8s.bin` | [xuebinqin/DIS](https://github.com/xuebinqin/DIS) `isnet-general-use` → [rembg](https://github.com/danielgatis/rembg) ONNX; statik int8 (QDQ, kanal başına) | Apache-2.0 | 1024×1024, (x/255-0.5) normalizasyonu, WASM |
