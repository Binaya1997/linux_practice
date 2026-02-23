 Linx File system
==================
File System : OS store and manage data on disk or partititons using structure called File System.

File system includes file,directories and its related permission.

Some Types of File system
=========================
#https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/7/html/storage_administration_guide/part-file-systems - To go detail

  1 ext3 
  2 ext4
  3 xfs [ Ubuntu,Debian,Fedora,Centos,Redhat ]
  4 Btrfs (B - tress fs) [ Open SUSE and SUSE Linux Enterprise Serer ]
  5 FAT - #https://www.geeksforgeeks.org/operating-systems/fat-full-form/

  How to check your linux Filesystem.
 =====================================
  lsblk-f
  df -Th
  cat /etc/fstab

  XFS vs ext4
  ===========

  XFS :- Optimise for large file and volume, offering superior performance and scalability.

  ext4 :- Perform well across various file size but less efficient with extremely largre file.
  
IMP: For High-through and extensive parallel processing capability xfs is typically more efficient then ext4.



  
