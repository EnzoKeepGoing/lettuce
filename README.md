# 🥬 Lettuce Phenotype Dataset from Multimodal Images

This dataset is associated with our research article published in *Computers and Electronics in Agriculture*:

**"Lettuce architectural phenotypes extraction from multimodal images by low-light sensitivity and strong spatial perception"**

📄 PDF: [Available Here]([link-to-paper-if-public](https://www.sciencedirect.com/science/article/pii/S0168169925000341?ref=pdf_download&fr=RR-2&rr=977331744e85099d))

---

## 📁 Dataset Description

- **Image Types**: RGB, Infrared (IR), and Depth images
- **Resolution**: 1280 × 720 (PNG format)
- **Camera**: Intel® RealSense™ D435i
- **Capture Setup**: Side view of cultivation frames, hourly images from 9:00 AM to 11:00 PM
- **Image Counts**:
  - Training Set: 9,000 images  
  - Validation Set: 8,000 images  
  - Test Set: 1,000 images  
- **Labels**: All images are annotated using LabelImg with bounding boxes labeled as `"lettuce"`
- **Lettuce Varieties**: Bixiao, Huqian, and Mondai

---

## 💡 Research Highlights

- A multimodal fusion model combining **RGB + IR + Depth** to extract lettuce architectural phenotypes in Plant Factories with Artificial Lighting (PFALs)
- Two novel modules:
  - `DRS`: Deep Residual Spatial Enhancement
  - `IRC`: Infrared Feature Compensation via Adaptive Weighting
- The model is robust under variable lighting and dense planting conditions
- Experimental results:        
  - **Plant Height RMSE**: 0.74 cm | **MSE**: 0.55  
  - **Canopy Width RMSE**: 0.70 cm | **MSE**: 0.49

---

## 🔗 Download        

- **Baidu Netdisk**: [百度网盘]((https://pan.baidu.com/s/1eMMEYPpSjWA8Gd2srSZlBQ?pwd=2aky)
- **Extraction Code**: `2aky`

> 📌 Please cite the paper below if you use this dataset.

---

## 📚 Citation (BibTeX)

```bibtex      
@article{lu2025lettuce,
  title={Lettuce architectural phenotypes extraction from multimodal images by low-light sensitivity and strong spatial perception},
  author={Lu, Shenglian and Lv, Yibo and Qian, Tingting and Ren, Wenyi and Li, Xiaoming and Li, Yiyang and Li, Guo},
  journal={Computers and Electronics in Agriculture},
  volume={232},
  pages={109928},
  year={2025},
  publisher={Elsevier},
  doi={10.1016/j.compag.2025.109928}
}
