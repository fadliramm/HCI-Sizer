# HCI Sizer

Kalkulator sizing Hyper-Converged Infrastructure (HCI) untuk vCPU, memori, dan storage, dari raw capacity hingga usable dan effective.

**Live:** https://fadliramm.github.io/HCI-Sizer/

## Fitur
- Preset brand: Nutanix, VMware vSAN ESA/OSA, Dell VxRail, Sangfor HCI, Proxmox VE + Ceph, Microsoft Azure Local, Generic
- Input spesifikasi per server: CPU, RAM, disk kapasitas & cache, network
- Waterfall raw → usable untuk storage, compute, dan memori
- Estimasi jumlah VM berdasarkan profil referensi
- Validasi desain (minimum node, proteksi, network, overhead)
- Mode perbandingan antar brand untuk spesifikasi hardware yang sama
- Export laporan ke PDF dan Excel (.xlsx)
- Dashboard eksekutif untuk presentasi ke manajemen (mode layar penuh)

Nilai default per brand adalah estimasi umum. Validasi dengan sizer resmi vendor untuk proposal final.

Satu file HTML statis, tanpa build step.
