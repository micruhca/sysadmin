virtual_machines = {
    "vm-1" = {
      vm_name      = "example-ubuntu-245" # Имя ВМ
      vm_desc      = "Описание для инженеров. Его видно только здесь"
      vm_cpu       = 2  # Кол-во ядер процессора
      ram          = 2  # Оперативная память в ГБ
      disk         = 20 # Объём диска в ГБ
      disk_name    = "vm1-system-disk" # Универсальное название
      template     = "ID_ОБРАЗА_ОС"   # Заменить на переменную или placeholder
      cloud_config = "cloud_config.yaml" # Убрать внутренние пути
    },
    "vm-2" = {
      vm_name      = "example-ubuntu-24"
      vm_desc      = "Описание для инженеров. Его видно только здесь"
      vm_cpu       = 2
      ram          = 2
      disk         = 20
      disk_name    = "vm2-system-disk"
      template     = "ID_ОБРАЗА_ОС"
      cloud_config = "cloud_config.yaml"
    },
    "vm-3" = {
      vm_name      = "example-ubuntu-244"
      vm_desc      = "Описание для инженеров. Его видно только здесь"
      vm_cpu       = 2
      ram          = 2
      disk         = 20
      disk_name    = "vm3-system-disk"
      template     = "ID_ОБРАЗА_ОС"
      cloud_config = "cloud_config.yaml"
    }
}