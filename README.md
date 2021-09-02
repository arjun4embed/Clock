# DS3231 BASED RTC CLOCK

## Description
   DS3231 based rtc clock implementation with menu to configure time,date and alarm
   
### Menu items 
- SET TIME
- SET DATE
- SET ALARM1
- SET ALARM2

### Date and time settings
 - Time functions :
 
        void ds3231_get_time(I2C_handle_t *pI2CHandle,RTC_Time_t  *pTime);
        void ds3231_set_time(I2C_handle_t *pI2CHandle,RTC_Time_t  *pTime);
 - Date functions :
  
        void ds3231_get_date(I2C_handle_t *pI2CHandle,RTC_Date_t *pdate);
        void ds3231_set_date(I2C_handle_t *pI2CHandle,RTC_Date_t *pdate);
  
  
## Useful links
   
  
* [stm32f407xx driver](https://github.com/arjun4embed/stm32f407xx-driver)
* [youtube](https://youtu.be/9XMcYJlmQfo)



