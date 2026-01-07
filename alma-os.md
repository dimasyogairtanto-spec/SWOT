**SWOT ALMA**

| **Strength**                                           | **Weakness**                                          | **Opportunity**                                                | **Threats**                                                  |
| ------------------------------------------------------ | ----------------------------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------------ |
| **support  RHEL** → stabil & konsisten                 | Kurang ramah untuk pemula karena **berbasis CLI**     | Tersedia **image ISO & QCOW2** untuk instalasi fisik & virtual | Persaingan dengan distro sejenis (Rocky Linux, Oracle Linux) |
| Keamanan default kuat (**SELinux & firewalld aktif**)  | SELinux membatasi konfigurasi aplikasi secara default | Cocok untuk **simulasi server produksi**                       | Ubuntu Server lebih populer                                  |
| Lifecycle panjang → jarang reinstall OS                | Paket software **tidak selalu versi terbaru**         | Digunakan sebagai **pengganti CentOS**                         | Ketergantungan pada kebijakan RHEL                           |
| Mendukung monitoring & manajemen via **Cockpit (GUI)** | Beberapa aplikasi tidak tersedia di repo resmi        | Standarisasi OS server                                         | Dukungan vendor resmi terbatas                               |
| Gratis & open source                                   | Setup awal relatif **lebih kompleks**                 | Stabil untuk penggunaan jangka panjang                         | Komunitas lebih kecil dibanding distro populer               |
| Dokumentasi lengkap & mudah ditemukan                  | Kurang optimal untuk penggunaan desktop               | Digunakan luas pada server Linux                               |                                                              |
|                                                        |                                                       |                                                                |                                                              |

**SWOT SPAROW DAN ALMA**

| **Strength**                                         | **Weakness**              | **Opportunity**                                                                                                                                      | **Threats**                              |
| ---------------------------------------------------- | ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| docker, podman, vm, libvirt tidak tersedia dari awal | tersedia secure boot      | sparow dapat langsung digunakan setelah instalasi tanpa perlu mengunduh aplikasi tambahan.                                                           | belum banyak dokumentasi mengenai sparow |
| tidak support sering ganti kernel                    | dokumentasi mudah di cari | **ketidakmampuan rollback saat kernel bermasalah, downtime lebih lama, kesulitan troubleshooting, dan risiko incompatibility hardware atau driver**. | lebih berat (karena memakai tampilan)    |
| berbasis cli                                         |                           | susah bagi pemula                                                                                                                                    |                                          |
