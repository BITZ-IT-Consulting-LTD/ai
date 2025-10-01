# 📊 Code Coverage Report - AI Service

**Branch:** 1/merge
**Commit:** [\`b7e1f6c\`](https://github.com/BITZ-IT-Consulting-LTD/ai/commit/b7e1f6c34910d342a9e38fc2cc34e5119ce16025)
**Generated:** 2025-10-01 17:04:48 UTC
**Python Version:** 3.12
**Workflow:** [\`18169547237\`](https://github.com/BITZ-IT-Consulting-LTD/ai/actions/runs/18169547237)

## 🎯 Coverage Summary

![Coverage](https://img.shields.io/badge/Coverage-48%25-orange)

| Metric | Value | Status |
|--------|-------|--------|
| **Coverage** | 48% | ❌ Fail |
| **Threshold** | 80% | Target |

## 📈 Detailed Coverage Report

```
Name                                         Stmts   Miss  Cover   Missing
--------------------------------------------------------------------------
app/__init__.py                                  1      0   100%
app/api/__init__.py                              0      0   100%
app/api/audio_routes.py                        277    192    31%   44, 111, 116, 149-151, 190, 198-200, 205-230, 235-240, 245-304, 313-341, 356-554, 572-668
app/api/call_session_routes.py                 223     67    70%   14-15, 117, 130-134, 145, 170-174, 182, 193, 210-237, 247, 251, 262, 273, 281-291, 296-306, 319-321, 327, 334, 349, 368-370, 382-390, 401-411
app/api/classifier_route.py                     49      6    88%   46, 79, 91, 99-106
app/api/health_routes.py                       101     43    57%   49-50, 119, 126-195, 218-240
app/api/ner_routes.py                           48     18    62%   41-85, 93, 102-105
app/api/qa_route.py                             47     19    60%   36-71, 80-84, 89-101
app/api/summarizer_routes.py                    48      0   100%
app/api/task_routes.py                         104     78    25%   34-93, 109-139, 152-195, 208-264
app/api/translator_routes.py                    36     15    58%   33-76, 84
app/api/whisper_routes.py                       77     44    43%   47, 62-126, 134-157, 165-194, 202
app/celery_app.py                               10      1    90%   7
app/config/__init__.py                           0      0   100%
app/config/settings.py                          82     17    79%   70-73, 111, 119-133
app/core/__init__.py                             0      0   100%
app/core/celery_monitor.py                      61     42    31%   21-93, 97, 106, 114
app/core/resource_manager.py                   118     25    79%   88-89, 134-135, 150-151, 166-167, 197, 201-206, 210-228, 235-239
app/core/streaming.py                          106     80    25%   22-29, 33-40, 44, 56-86, 96, 118, 141-143, 160, 175, 193-261, 265-283, 287-294
app/core/text_chunker.py                       156     26    83%   70-72, 77-79, 86-90, 98, 158-182, 290
app/main.py                                    113     69    39%   36-99, 133, 138-141, 150, 179-200, 215-218, 222-243
app/model_scripts/__init__.py                    7      0   100%
app/model_scripts/classifier_model.py          221     68    69%   21-29, 32-48, 86, 107-110, 120, 125, 149-153, 171, 188-193, 200-241, 265-268, 279, 282, 337-340, 355, 370, 385, 390, 397
app/model_scripts/model_loader.py              220    140    36%   15-17, 23-25, 31-33, 39-41, 47-49, 55-57, 63-65, 131, 149, 156-157, 163-166, 170-302, 306-319, 323-328, 347, 353, 358, 363, 368, 373, 379
app/model_scripts/ner_model.py                  74     15    80%   32-34, 41-43, 50, 59-63, 107-109
app/model_scripts/qa_model.py                  137     90    34%   52-56, 62-68, 101-118, 138-198, 215-240, 262-317, 322, 326-328
app/model_scripts/summarizer_model.py          160     68    58%   36, 43, 73-77, 108-113, 135-137, 147-209, 221, 226-251, 256, 274, 290, 295, 304-306, 311, 323-325
app/model_scripts/translator_model.py          149     91    39%   40, 77-102, 106-130, 134-171, 177-195, 199-228, 232-234, 247-263, 268, 277-278
app/model_scripts/whisper_model.py             203     56    72%   25-26, 86-87, 143-144, 170-180, 210, 232, 236, 242, 247, 265, 276-335, 362-383, 414
app/models/__init__.py                           0      0   100%
app/models/model_loader.py                      12     12     0%   2-18
app/services/agent_notification_service.py     216    153    29%   58-65, 72-73, 77-122, 126-146, 150-152, 156-162, 166-181, 188-249, 253-261, 266-275, 280-290, 295-310, 315-328, 333-344, 348-357, 361-370, 374-382, 392-445, 450-460, 466-475, 479-505, 515-544, 548-557
app/streaming/__init__.py                        3      0   100%
app/streaming/audio_buffer.py                   40      0   100%
app/streaming/call_session_manager.py          503    281    44%   20-22, 100-102, 150-151, 158-165, 173-175, 214-219, 246-250, 256-257, 266-269, 282-283, 296-298, 344-346, 350-453, 457-479, 483-513, 517-576, 586-601, 605-683, 733-734, 767, 771-772, 807-816, 822-824, 828-877, 881-1014, 1018-1047
app/streaming/progressive_processor.py         245     10    96%   15-17, 78, 124, 361-363, 375-376
app/streaming/tcp_server.py                    101      0   100%
app/streaming/websocket_server.py               57      0   100%
app/tasks/__init__.py                            0      0   100%
app/tasks/audio_tasks.py                       616    585     5%   24-48, 55-194, 207-225, 236-290, 306-811, 824-879, 885-896, 948-1091, 1111-1473
app/tasks/inference_tasks.py                   188    165    12%   12-13, 30-111, 116-153, 158-175, 191-232, 249-292, 309-351, 366-406, 423-465
app/utils/__init__.py                            0      0   100%
app/utils/scp_audio_downloader.py              130     90    31%   79-107, 117-119, 126-137, 144-145, 158-220, 242-272, 280-291, 296-302
--------------------------------------------------------------------------
TOTAL                                         4939   2566    48%
```

---
*Report generated automatically by GitHub Actions*
*Access this report at: [COVERAGE.md](https://github.com/BITZ-IT-Consulting-LTD/ai/blob/1/merge/ai_service/COVERAGE.md)*
