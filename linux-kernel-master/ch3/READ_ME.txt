* 3.1.2

   ; patch_source_file/linux/kernel/irq/proc.c (1��: 83������)
      rpi_get_interrupt_info() �Լ��� �߰��� �ҽ� �ڵ�

   ; rpi_get_interrupt_info_callstack_ftrace_log.c (1��: 87/88������)
      rpi_get_interrupt_info() �Լ��� �� ������ ���Ե� ftrace �α�

   ; bcm2835_mmc_irq_callstack_ftrace_log.c (1��: 90������)
      bcm2835_mmc_irq() �Լ��� �� ������ ���Ե� ftrace �α�

   ; irq_trace_ftrace.sh (1��: 87 ������)
      ftrace�� �����ϱ� ���� �� ��ũ��Ʈ ����

   ; get_ftrace.sh  
      ftrace �α׸� �����ϴ� �� ��ũ��Ʈ ����

* 3.4.4

   ; get_ftrace.sh (1��: 113 ������)
      ftrace �α׸� �����ϴ� �� ��ũ��Ʈ ����

* 3.6

   ; patch_source_file/linux/drivers/soc/bcm (1��: 122������)
      rpi_debugfs.c: �ҽ� ����
      Makefile: rpi_debugfs.c �ҽ� ������ �����ϱ� ���� ����ũ ����

   ; patch_source_file/linux/kernel/irq/handle.c (1��: 125������)
     raspbian_debug_state ���� ������ Ȱ���� ��ġ �ڵ�
