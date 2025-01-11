# Comparative Shark Genomics

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Methods](#methods)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Köpek balıkları, deniz ekosistemlerinde önemli bir rol oynayan ve uzun evrimsel geçmişe sahip olan hayvanlardır. Genetik yapılarının diğer canlılarla karşılaştırılması, evrimsel ilişkilerin anlaşılmasına ve biyolojik çeşitliliğin korunmasına katkıda bulunabilir. Bu proje, farklı köpek balığı türlerinin nükleotit yapılarını diğer organizmalarla karşılaştırarak benzerliklerini kümelerle analiz etmeyi amaçlamaktadır.

## Project Overview

Bu proje, çeşitli köpek balığı türlerinin nükleotit dizilerini analiz ederek diğer canlılarla genetik benzerliklerini incelemektedir. Kullanılan yöntemler arasında veri toplama, ön işleme, benzerlik hesaplama ve kümeleme yer almaktadır. Sonuçlar, köpek balığı türlerinin genetik yakınlıklarına göre sınıflandırılmasını sağlar.

## Methods

1. **Data Collection**: Köpek balığı ve diğer organizmaların nükleotit dizileri çeşitli biyoinformatik veri tabanlarından toplandı.
2. **Data Preprocessing**: Ham veriler temizlendi, hizalandı ve analiz için uygun formata dönüştürüldü.
3. **Similarity Calculation**: Nükleotit dizileri arasındaki benzerlikler hesaplandı.
4. **Clustering**: Benzerlik matrisine dayanarak kümeleme algoritmaları (örn. K-Means, Hierarchical Clustering) kullanılarak türler gruplandırıldı.
5. **Visualization**: Sonuçlar dendrogramlar ve diğer görselleştirme araçları ile sunuldu.

## Results

- Köpek balığı türleri genetik benzerliklerine göre başarılı bir şekilde kümelendi.
- Analiz, bazı köpek balığı türlerinin diğer organizmalarla yüksek genetik yakınlık gösterdiğini ortaya koydu.
- Filogenetik ağaçlar, evrimsel ilişkilerin daha iyi anlaşılmasını sağladı.

![Clustering Results](https://example.com/clustering-results.png) <!-- Sonuç görseli ekleyebilirsiniz -->

## Installation

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

1. **Repository'yi Klonlayın**
    ```bash
    git clone https://github.com/berkayhancer21/Shark-Nucleotide-Clustering.git

    cd Shark-Nucleotide-Clustering
    ```

2. **Gerekli Paketleri Yükleyin**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Jupyter Notebook dosyasını çalıştırmak için:

1. **Jupyter Notebook'u Başlatın**
    ```bash
    jupyter notebook
    ```

2. **`shark_genome_comparison_and_clustering.ipynb` Dosyasını Açın**

Notebook içerisinde adım adım analizleri gerçekleştirebilir ve sonuçları görüntüleyebilirsiniz.

## Dependencies

Projede kullanılan başlıca Python kütüphaneleri şunlardır:

- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Biopython](https://biopython.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

Tüm bağımlılıkları `requirements.txt` dosyasından yükleyebilirsiniz.

## Contributing

Katkıda bulunmak isterseniz, lütfen [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını inceleyin. Her türlü katkıya açığız!

## License

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına bakabilirsiniz.

## Acknowledgements

- **OpenAI** - Profesyonel asistan desteği.
- **NCBI** - Genetik veri sağlayan veri tabanı.
- **Python Community** - Kullanılan kütüphaneler ve araçlar için teşekkürler.

---

© 2025 [Berkay HANÇER](https://github.com/berkayhancer21)
