

## 捕鱼科技


上传


url:
http://www.cv-parser.com/PekeUploadJSON
method:post
Content-Type:form-data
body:
key:cv  value:/Users/wanghaisheng/workspace/resume-parse-evaluation/resume-samples/pdf/西安电子科技大学-通信与信息系统-硕士-邢亚英.pdf





解析


url:
http://www.cv-parser.com/resume
method:post
Content-Type:application/x-www-form-urlencoded


body:
step:analyze
file_name_original:西安电子科技大学-通信与信息系统-硕士-邢亚英.pdf



从得到的html中抠出以下内容 但么有构造出能直接得到这个 candidate 字符串的请求

```
            var candidate ={"candidate_id":1142,"user_id":1,"cv_source":0,"cv_type":1,"cv_update_time":"","photo_name":"1142-20180418001500.jpg","name_chi":"邢亚英","name_eng":"","mobile":"86-15991614286","email":"xing_yaying@126.com","email_flag":1,"sex":0,"height":0,"weight":0,"qq":"","wechat":"","marital_status":0,"degree":4,"birthday":"1988-03-01","start_work_time":"2008-11-01","id_card":"","nationality_from_chi_cv":"","nationality_from_eng_cv":"","ethnicity_from_chi_cv":"","ethnicity_from_eng_cv":"","political_status_from_chi_cv":"中共党员","political_status_from_eng_cv":"","native_place_from_chi_cv":"山西忻州","native_place_from_eng_cv":"","household_registration_from_chi_cv":"","household_registration_from_eng_cv":"","location_from_chi_cv":"陕西省西安市雁塔区西安电子科技大学","location_from_eng_cv":"","company_from_chi_cv":"","company_from_eng_cv":"","industry_from_chi_cv":"","industry_from_eng_cv":"","job_title_from_chi_cv":"测试工程师","job_title_from_eng_cv":"","job_function_from_chi_cv":"","job_function_from_eng_cv":"","current_situation_from_chi_cv":"","current_situation_from_eng_cv":"","expected_location_from_chi_cv":"西安","expected_location_from_eng_cv":"","expected_job_nature_from_chi_cv":"","expected_job_nature_from_eng_cv":"","expected_job_function_from_chi_cv":"测试工程师","expected_job_function_from_eng_cv":"","expected_job_industry_from_chi_cv":"","expected_job_industry_from_eng_cv":"","standard_job_function_from_chi_cv":"测试","standard_job_function_from_eng_cv":"","standard_job_industry_from_chi_cv":"","standard_job_industry_from_eng_cv":"","chi_current_location_address":"陕西省西安市雁塔区西安电子科技大学","chi_current_location_country":"中国","chi_current_location_province":"陕西省","chi_current_location_city":"西安市","chi_current_location_district":"雁塔区","eng_current_location_address":"","eng_current_location_country":"","eng_current_location_province":"","eng_current_location_city":"","eng_current_location_district":"","current_salary_min":0,"current_salary_max":0,"expected_salary_min":0,"expected_salary_max":0,"predicted_salary_min":0,"predicted_salary_max":0,"chi_university_work":"","eng_university_work":"","chi_social_work":"","eng_social_work":"","chi_training_experience":"","eng_training_experience":"","chi_award":" 2011.09---2013.10 西安电子科技大学一等奖学金(三年)\n 2009.10 长安大学第八届电子设计竞赛一等奖\n 2008.09---2009.07 国家励志奖学金\n 2007.09---2008.07 长安大学信息工程学院“院级三好学生”\n 2006.09---2007.07 长安大学单项奖学金\n","eng_award":"","chi_certificates":"","eng_certificates":"","chi_hobbies":"","eng_hobbies":"","chi_personal_work":"","eng_personal_work":"","chi_language_skills":"","eng_language_skills":"","chi_computer_skills":"","eng_computer_skills":"","chi_skills":" 具有扎实的数学基础和关于无线通信尤其是认知无线电的背景知识和专业理论\n 熟悉 Python 编程语言(工作于 Linux 系统下)\n 熟悉 C/C++编程语言,通过计算机二级与三级,熟悉计算机网络编程\n 熟悉 Delphi 编程工具,使用 LabView 完成本科毕业论文,使用 Matlab 进行数字信号处理仿真\n英语能力\n 通过英语四级和六级考试\n 参加过口语培训课程,具备良好的英语听说能力\n 研究生阶段阅读了大量英文文献,具有优秀的英文读写能力和文献翻译能力\n","eng_skills":"","chi_self_evaluation":" 记忆力好,学习能力强,能很快接受新鲜事物和不同环境\n 有上进心、责任心,做事认真专注、井井有条\n 善于与人相处,具备良好的表达能力和团队协作能力,能够承受压力和挫折\n 性格稳重,喜欢象棋及各类运动,如羽毛球、跑步、爬山等\n","eng_self_evaluation":"","chi_candidate_report":"","eng_candidate_report":"","create_time":"Feb 9, 2018 5:06:09 PM","modify_time":"Apr 18, 2018 12:15:00 AM","educationList":[{"id":13343,"candidate_id":1142,"lang_flag":1,"start_time":"2011-08-01","end_time":"2014-04-01","institution_name":"西安电子科技大学","institution_ranking":988,"institution_tag":2,"education_level":4,"education_field":"工学","education_description":"","create_time":"Apr 18, 2018 12:15:00 AM","modify_time":"Apr 18, 2018 12:15:00 AM","institution_tag_text":"211","education_level_text":"硕士"},{"id":13344,"candidate_id":1142,"lang_flag":1,"start_time":"2006-09-01","end_time":"2010-07-01","institution_name":"长安大学","institution_ranking":965,"institution_tag":2,"education_level":3,"education_field":"工学","education_description":"主修课程\n 研究生课程\n通信网络基础,宽带无线通信,数字信号处理(二),网络多媒体,数值分析,工程优化方法,\n随机过程,英语基础,英语视听说,专业英语阅读等\n 本科生课程\n通信原理,移动通信,信号与系统,数字信号处理,智能仪器,电子测量技术,自动控制原理,\n数据通信与计算机网络,锁相环,单片机,微机原理,电路基础,EDA 设计,C 语言等\n","create_time":"Apr 18, 2018 12:15:00 AM","modify_time":"Apr 18, 2018 12:15:00 AM","institution_tag_text":"211","education_level_text":"本科"}],"projectList":[],"workList":[{"id":27683,"candidate_id":1142,"lang_flag":1,"start_time":"2011-09-01","end_time":"2013-10-01","salary_min":0,"salary_max":0,"subordinate_num":0,"company_name":"西安电子科技大学","company_industry":"","company_industry_standard":"","company_ranking":0,"company_type":0,"company_size_min":0,"company_size_max":0,"company_intro":"","location":"","job_title":"","job_title_standard":"","job_function":"","report_to":"","leave_reason":"","job_result":"","job_description":" 2009.10 长安大学第八届电子设计竞赛一等奖\n 2008.09---2009.07 国家励志奖学金\n 2007.09---2008.07 长安大学信息工程学院“院级三好学生”\n 2006.09---2007.07 长安大学单项奖学金","create_time":"Apr 18, 2018 12:15:00 AM","modify_time":"Apr 18, 2018 12:15:00 AM","company_type_text":""},{"id":27681,"candidate_id":1142,"lang_flag":1,"start_time":"2010-07-01","end_time":"2010-09-01","salary_min":0,"salary_max":0,"subordinate_num":0,"company_name":"上海红会信息科技有限公司","company_industry":"","company_industry_standard":"","company_ranking":89,"company_type":0,"company_size_min":0,"company_size_max":0,"company_intro":"","location":"上海","job_title":"测试工程师","job_title_standard":"测试","job_function":"","report_to":"","leave_reason":"","job_result":"","job_description":"并独自对网页登录系统进行功能测试并提交 bug\n 2009.09 第九届“NEC 电子杯”全国大学生电子设计竞赛,参赛作品:声音引导系统","create_time":"Apr 18, 2018 12:15:00 AM","modify_time":"Apr 18, 2018 12:15:00 AM","company_type_text":""},{"id":27680,"candidate_id":1142,"lang_flag":1,"start_time":"2009-09-01","end_time":"2009-09-01","salary_min":0,"salary_max":0,"subordinate_num":0,"company_name":"声音引导系统","company_industry":"","company_industry_standard":"","company_ranking":0,"company_type":0,"company_size_min":0,"company_size_max":0,"company_intro":"","location":"","job_title":"辅导机构高中数学老师","job_title_standard":"","job_function":"","report_to":"","leave_reason":"","job_result":"","job_description":"担任小组组长。主要负责整体方案的论证选择,系统理论分析与计算,包括数学模型\n的建立、误差分析、位置式 PID 控制理论分析,以及对系统的测试,对测试结果的分析,竞赛报告的\n撰写。\n实践经验\n 2011.11 通信工程学院研究生辩论赛,担任反方四辩\n 2011.10---2013.05 辅导机构担任高中数学老师,今年所带班级(约 25 人)参加高考,大部分\n学生取得了很好的成绩,我得到辅导机构负责人的肯定","create_time":"Apr 18, 2018 12:15:00 AM","modify_time":"Apr 18, 2018 12:15:00 AM","company_type_text":""},{"id":27682,"candidate_id":1142,"lang_flag":1,"start_time":"2008-11-01","end_time":"","salary_min":0,"salary_max":0,"subordinate_num":0,"company_name":"多功能信号发生器","company_industry":"","company_industry_standard":"","company_ranking":0,"company_type":0,"company_size_min":0,"company_size_max":0,"company_intro":"","location":"德州","job_title":"","job_title_standard":"","job_function":"","report_to":"","leave_reason":"","job_result":"","job_description":" 2008.08 2008 年“德州仪器(TI)杯”电子竞赛,参赛作品:智能避障小车\n获奖情况","create_time":"Apr 18, 2018 12:15:00 AM","modify_time":"Apr 18, 2018 12:15:00 AM","company_type_text":""}],"cv_source_en":"","cv_source_zh_CN":"","sex_en":"","sex_zh_CN":"","degree_en":"Master","degree_zh_CN":"硕士","marital_status_en":"","marital_status_zh_CN":""};

```




