* 5.2.2

   ; irq_stack_trace.sh (1��: 295������)
      ftrace�� �����ϱ� ���� �� ��ũ��Ʈ ����

   ; ftrace_log.c (1��: 296������)
      ftrace �α� ����

   ; get_ftrace.sh  
      ftrace �α׸� �����ϴ� �� ��ũ��Ʈ ����

* 5.2.3

   ; patch_source_file/linux/mmc/host/bcm2835-sdhost.c (1��: 312������)
      bcm2835_sdhost_irq() �Լ��� ��ġ �ڵ带 �߰��� �ҽ� ����

   ; 5.2.3_in_interrupt.patch (1��: 312������)
      ��ġ ����(�ҽ� �ڵ��� �������� ǥ��)

   ; kern.log (1��: 314������)
      Ŀ�� �α�(/var/log/kern.log)

* 5.4.2/334_������_�ǽ�

   ; patch_source_file/linux/kernel/irq/manage.c (1��: 334������)
      request_threaded_irq() �Լ��� ��ġ �ڵ带 �߰��� �ҽ� ����

   ; 5_4_2_request_threaded_irq.patch (1��: 334������)
      ��ġ ����(�ҽ� �ڵ��� �������� ǥ��)

   ; kern.log (1��: 337������)
      Ŀ�� �α�(/var/log/kern.log)

* 5.4.2/339_������_�ǽ�
 
   ; patch_source_file/linux/drivers/usb/host/dwc_otg/dwc_otg_driver.c (1��: 339������)
     dwc_otg_driver_probe() �Լ��� ��ġ �ڵ�[interrupt_debug_irq_desc() �Լ�]�� �߰��� �ҽ� ���� 

   ; 5.4.2.interrupt_debug_irq_desc.patch (1��: 339~340������)
      ��ġ ����(�ҽ� �ڵ��� �������� ǥ��)

   ; kern.log (1��: 342������)
      Ŀ�� �α�(/var/log/kern.log)

* 5.5.2 
 
   ; patch_source_file/linux/drivers/mmc/host/bcm2835-mmc.c (1��: 353������)
      bcm2835_mmc_thread_irq() �Լ��� ��ġ �ڵ�[interrupt_debug_irq_times() �Լ�]�� �߰��� �ҽ� ���� 

   ; 5.5.2.interrupt_debug_irq_times.patch (1��: 353������)
      ��ġ ����(�ҽ� �ڵ��� �������� ǥ��)

   ; kern.log (1��: 355������)
      Ŀ�� �α�(/var/log/kern.log)

* 5.7.2

   ; irq_ftrace.sh (1��: 367������)
      ftrace�� �����ϱ� ���� �� ��ũ��Ʈ ����

   ; ftrace_log.c (1��: 367������)
      ftrace �α� ����

   ; get_ftrace.sh  
      ftrace �α׸� �����ϴ� �� ��ũ��Ʈ ����

* 5.7.3

   ; patch_source_file/linux/kernel/irq/handle.c (1��: 372������)
      __handle_irq_event_percpu() �Լ��� ��ġ �ڵ带 �߰��� �ҽ� ���� 

   ; irq_ftrace.sh (1��: 367������)
      ftrace�� �����ϱ� ���� �� ��ũ��Ʈ ����

   ; ftrace_log.c (1��: 372������)
      ftrace �α� ����

   ; get_ftrace.sh  
      ftrace �α׸� �����ϴ� �� ��ũ��Ʈ ����
