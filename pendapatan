# sistem-panen-fathan
Tugas Terstruktur BAB IV Nomor 4
def hitung_pendapatan(data_penjualan):
    """
    Menghitung total seluruh pendapatan dari daftar transaksi.
    """
    total_pendapatan = 0
    for item in data_penjualan:
        total_pendapatan += item["harga"] * item["jumlah"]
    return total_pendapatan
def cetak_laporan(data_penjualan):
    """
    Mencetak ringkasan laporan transaksi dan total pendapatan.
    """
    print("=" * 45)
    print("           LAPORAN PENJUALAN UTAMA           ")
    print("=" * 45)
    print(f"{'Nama Barang':<15} | {'Harga':<10} | {'Qty':<5} | {'Subtotal':<10}")
    print("-" * 45)
    for item in data_penjualan:
        subtotal = item["harga"] * item["jumlah"]
        print(f"{item['nama']:<15} | Rp{item['harga']:<8} | {item['jumlah']:<5} | Rp{subtotal:<8}") 
    print("-" * 45)
    total = hitung_pendapatan(data_penjualan)
    print(f"Total Pendapatan : Rp{total:,}".replace(',', '.'))
    print("=" * 45)
