* 8.2.3

   ; patch_source_file/linux/kernel/time/timekeeping.c (2��: 14������)
      do_timer() �Լ��� ��ġ �ڵ带 �߰��� �ҽ� ����

   ; do_timer_jiffies_debug.patch (2��: 14������)
      ��ġ ����(�ҽ� �ڵ��� �������� ǥ��)

   ; do_timer_debug.sh (2��: 15������)
      ftrace�� �����ϱ� ���� �� ��ũ��Ʈ ����

   ; jiffies_ftrace_log.c (2��: 15������)
      ftrace �α� ����: jiffies ���� ����

   ; do_timers_callstack_ftrace_log.c (2��: 17������)
      ftrace �α� ����: do_timer() �Լ��� �� ����

   ; get_ftrace.sh  
      ftrace �α׸� �����ϴ� �� ��ũ��Ʈ ����	  
	  
* 8.7.1

   ; timer_ftrace_setting.sh (2��: 69������)
      ftrace�� �����ϱ� ���� �� ��ũ��Ʈ ����

   ; ftrace_log.c (2��: 69������)
      ftrace �α� ����

   ; get_ftrace.sh  
      ftrace �α׸� �����ϴ� �� ��ũ��Ʈ ����

* 8.7.2

   ; patch_source_file/linux/drivers/usb/core/hcd.c (2��: 74������)
   ; patch_source_file/linux/kernel/softirq.c  
   ; patch_source_file/linux/kernel/time/timer.c  
      ���� Ÿ�̸� �ǽ� �ҽ� ����

  ; patch_source_file/linux/drivers/soc/bcm
      rpi_debugfs �ҽ� ����: rpi_debugfs.c, Makefile

   ; dynamic_timer_debug.patch (2��: 74������)
      ��ġ ����(�ҽ� �ڵ��� �������� ǥ��)

   ; timer_debug_raspbian.sh (2��: 82������)
      ftrace�� �����ϱ� ���� �� ��ũ��Ʈ ����

   ; ftrace_log.c (2��: 84������)
      ftrace �α� ����
 