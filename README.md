# DDoS Saldırı Tespit Sistemi

Bu proje, DDoS (Distributed Denial of Service) saldırılarını tespit etmek için geliştirilmiş bir sistemdir.

## Özellikler

- DDoS saldırılarının gerçek zamanlı tespiti
- Jupyter Notebook üzerinde veri analizi ve görselleştirme
- Makine öğrenmesi modelleri ile anomali tespiti

## Veri Seti

Proje, SDN (Software Defined Networking) tabanlı bir DDoS saldırı tespit veri seti kullanmaktadır. Veri seti `data/dataset_sdn.csv` dosyasında bulunmaktadır ve şu özellikleri içerir:

- Ağ trafiği özellikleri (paket sayısı, byte sayısı, süre vb.)
- Protokol bilgileri
- Kaynak ve hedef IP adresleri
- Port numaraları
- Saldırı etiketleri (normal/saldırı)

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/hdemirz/DDos-Detection.git
cd DDos-Detection
```

2. Gerekli Python paketlerini yükleyin:
```bash
pip install -r requirements.txt
```

## Kullanım

1. Jupyter Notebook'u başlatın:
```bash
jupyter notebook
```

2. `DDOs.ipynb` dosyasını açın ve hücreleri sırasıyla çalıştırın.

## Katkıda Bulunma

1. Bu repository'yi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/yeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -am 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/yeniOzellik`)
5. Pull Request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.
