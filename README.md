# public
public of materials
2021年10月7日新增mariadb 10内存中搜索数据结构，搜索完毕树上返回block_t结构，入参为么加锁S LATCH OR X-LATCH？？？ ,为提高并发
入参mode为空，不要加锁。新增函数btr_root_block_get_no_latch函数