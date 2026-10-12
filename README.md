==Process1 service log == 
10-12 09:00:06.761
fms
[ZoneManager:zone_3_p0][REPLAN] Robot SEC_Process_1 stuck idle 16.0s (cur=A04 goal=CHP2) → replan
10-12 09:00:10.317
fms
[ZoneManager:zone_3_p0][JOINT-REPAIR] 이동 9 → 7 (최단 합 7) [SEC_Logistics_1,SEC_Process_1] states=1161 18.9ms
10-12 09:00:10.472
fms
[2026-10-12 09:00:10.472] [info] [09:00:10] [ACTION_MANAGER:zone_3_p0] robot SEC_Process_1 ENQUEUE fire 4 edge(s): A04 → A04 (async batch)
10-12 09:00:10.673
fms
[2026-10-12 09:00:10.673] [info] [09:00:10] [ACTION_MANAGER:zone_3_p0] robot SEC_Process_1 ENQUEUE 4 ok + 0 timeout(낙관): A04 → A04
10-12 09:00:12.139
fms
[2026-10-12 09:00:12.138] [info] [09:00:12] [SAFETY] robot=SEC_Process_1 'none' -> 'sf_operational_stop' level=1 sent_depth=0 robot_queue=0 state=stop cur=A04 age=283
10-12 09:00:12.139
fms
[Manager][SAFETY] robot='SEC_Process_1' 안전상태 진입 → 계획 제외 @A04
10-12 09:00:12.139
fms
[ZoneManager:zone_3_p0][REPLAN] Force replan: 안전상태 리셋: SEC_Process_1
10-12 09:00:12.274
fms
[2026-10-12 09:00:12.274] [info] [09:00:12] [ACTION_MANAGER:zone_3_p0] robot SEC_Process_1 safety reset → sent-chain clear (SendStop 없음: 로봇이 이미 정지)
10-12 09:00:12.876
fms
[ACTION_MANAGER:zone_3_p0][UNKNOWN-FUTURE] robot SEC_Logistics_1 경로를 보냄 — 상대 'SEC_Process_1' 는 남은 명령이 없어 **미래를 모르는데** 경로와 1.867m (반경 합 1.350, 밴드 1.50배). 그 로봇이 전진하면 겹칠 수 있다
10-12 09:00:15.342
fms
[2026-10-12 09:00:15.342] [info] [09:00:15] [SAFETY] robot=SEC_Process_1 'sf_operational_stop' -> 'none' level=0 sent_depth=0 robot_queue=0 state=stop cur=A04 age=480
10-12 09:00:15.342
fms
[Manager][SAFETY] robot='SEC_Process_1' 안전상태 해제 → 재계획
10-12 09:00:15.343
fms
[ZoneManager:zone_3_p0][REPLAN] Force replan: 안전상태 리셋: SEC_Process_1
10-12 09:00:16.182
fms
[2026-10-12 09:00:16.182] [warning] [09:00:16] [CollisionMonitor] pair=(SEC_Logistics_1,SEC_Process_1) NEAR-MISS dist=1.925 need=1.604 model=box r_sum=1.350 pos1=(8.864,16.992) pos2=(9.388,18.844) yaw1=-2.874337 yaw2=3.141376 state1=move state2=stop path_time1=0 path_time2=0
10-12 09:00:18.685
fms
[2026-10-12 09:00:18.685] [info] [09:00:18] [CollisionMonitor] pair=(SEC_Logistics_1,SEC_Process_1) recovered dist=1.842 need=1.533 model=box
10-12 09:00:20.482
fms
[ActionManager] SendStop 생략 robot=SEC_Process_1 reason=safety_release (no_pending_command)
10-12 09:00:20.482
fms
[2026-10-12 09:00:20.482] [info] [09:00:20] [ACTION_MANAGER:zone_3_p0] robot SEC_Process_1 safety reset → sent-chain clear (SendStop 생략: 보낸 명령 없음)
10-12 09:00:20.482
fms
[CommZenoh] Sent move to SEC_Process_1 on topic [amr/SEC_Process_1/move/goal] (cmd: goal, goal: CHP2, method: pp)
10-12 09:00:20.989
fms
[2026-10-12 09:00:20.989] [warning] [09:00:20] [CollisionMonitor] pair=(SEC_Logistics_1,SEC_Process_1) NEAR-MISS dist=1.614 need=1.370 model=box r_sum=1.350 pos1=(10.004,17.355) pos2=(9.388,18.846) yaw1=-2.824657 yaw2=-3.141349 state1=move state2=stop path_time1=0 path_time2=0
10-12 09:00:21.148
fms
[2026-10-12 09:00:21.148] [info] [09:00:21] [SAFETY] robot=SEC_Process_1 'none' -> 'sf_operational_stop' level=1 sent_depth=0 robot_queue=0 state=stop cur=A04 age=267
10-12 09:00:21.148
fms
[Manager][SAFETY] robot='SEC_Process_1' 안전상태 진입 → 계획 제외 @A04
10-12 09:00:25.885
fms
[2026-10-12 09:00:25.885] [info] [09:00:25] [ACTION_MANAGER:zone_3_p0] robot SEC_Process_1 safety reset → sent-chain clear (SendStop 없음: 로봇이 이미 정지)
10-12 09:00:25.885
fms
[ACTION_MANAGER:zone_3_p0][UNKNOWN-FUTURE] robot SEC_Logistics_1 경로를 보냄 — 상대 'SEC_Process_1' 는 남은 명령이 없어 **미래를 모르는데** 경로와 1.604m (반경 합 1.350, 밴드 1.50배). 그 로봇이 전진하면 겹칠 수 있다
10-12 09:00:25.999
fms
[2026-10-12 09:00:25.999] [warning] [09:00:25] [CollisionMonitor] pair=(SEC_Logistics_1,SEC_Process_1) NEAR-MISS dist=2.148 need=1.885 model=box r_sum=1.350 pos1=(11.241,17.758) pos2=(9.387,18.843) yaw1=-2.860133 yaw2=-3.141099 state1=move state2=stop path_time1=0 path_time2=0
10-12 09:00:26.360
fms
[ZoneManager:zone_3_p0][REPLAN] Force replan: 안전상태 리셋: SEC_Process_1, 정체 복구/안전상태 리셋 처리
10-12 09:00:27.202
fms
[2026-10-12 09:00:27.201] [info] [09:00:27] [CollisionMonitor] pair=(SEC_Logistics_1,SEC_Process_1) recovered dist=2.317 need=1.912 model=box
10-12 09:00:31.362
fms
[2026-10-12 09:00:31.362] [info] [09:00:31] [SAFETY] robot=SEC_Process_1 'sf_operational_stop' -> 'none' level=0 sent_depth=0 robot_queue=0 state=stop cur=A04 age=452
10-12 09:00:31.362
fms
[Manager][SAFETY] robot='SEC_Process_1' 안전상태 해제 → 재계획
10-12 09:00:31.362
fms
[ZoneManager:zone_3_p0][REPLAN] Force replan: 안전상태 리셋: SEC_Process_1

== 인터락 로그 ==
2026. 10. 12. 오전 9:17:07	cross_a	auto:lock	성공	—	auto	대기노드에 우리 로봇 도착 — 타사 락 요청/확인 대기(장애물 유지)
2026. 10. 12. 오전 9:03:25	cross_a	auto:unlock	성공	—	auto	타사 락 반납 중 — 브릿지가 해제를 보고할 때까지 재전송
2026. 10. 12. 오전 9:03:21	cross_a	auto:block	성공	—	auto	작업 완료 — 재차단 후 정착 대기(반납 전 필수)
2026. 10. 12. 오전 9:02:55	cross_a	auto:lock	성공	—	auto	타사 정지 확인됨 — 구역 개방, 우리 로봇 작업 중
2026. 10. 12. 오전 9:01:56	cross_a	auto:unblock	성공	—	auto	TrafficLocked=true, CurrentNode=A00, Status=RunIdle, 연속 1/1
2026. 10. 12. 오전 9:01:55	cross_a	auto:lock	성공	—	auto	대기노드에 우리 로봇 도착 — 타사 락 요청/확인 대기(장애물 유지)
2026. 10. 12. 오전 9:01:05	cross_a	auto:unlock	성공	—	auto	타사 락 반납 중 — 브릿지가 해제를 보고할 때까지 재전송
2026. 10. 12. 오전 9:00:54	cross_a	auto:lock	성공	—	auto	대기노드에 우리 로봇 도착 — 타사 락 요청/확인 대기(장애물 유지)
2026. 10. 12. 오전 9:00:20	cross_a	auto:unlock	성공	—	auto	타사 락 반납 중 — 브릿지가 해제를 보고할 때까지 재전송
2026. 10. 12. 오전 9:00:09	cross_a	auto:lock	성공	—	auto	대기노드에 우리 로봇 도착 — 타사 락 요청/확인 대기(장애물 유지)

=== FMS 로그 ==
38줄 표시 · 일치 38 / 읽음 216993 · 서버 712ms / 화면 775ms
fms 38/216993
 줄바꿈
 실시간 따라가기(10분)
10-12 08:33:24.200
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L27 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:35:49.679
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L22 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:37:32.998
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_2 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:38:30.382
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_3 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:40:39.708
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE1_1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:43:51.312
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L11 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:51:37.210
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L14 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:54:12.012
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L22 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:56:31.341
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_2 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 08:57:38.980
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_3 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 09:14:16.902
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_2 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 09:19:58.168
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L16 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 09:25:08.057
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 CHL1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 09:58:33.387
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L18 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 10:01:32.712
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_3 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 10:03:52.083
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE1_1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 10:05:56.265
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L10 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 10:11:04.832
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L18 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 10:43:27.504
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 CHL1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 11:14:52.889
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_2 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 11:16:16.587
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 CHL1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 11:18:10.986
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_2 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 11:28:06.624
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE2_2 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 11:36:41.956
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 CHL1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 16:42:59.603
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE2_1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 16:44:56.228
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L11 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 16:46:52.943
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L19 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 16:50:22.453
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 16:52:06.926
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE1_1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 16:58:56.677
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L19 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 17:01:43.434
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 CHL1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 17:03:58.143
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE2_1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 17:07:39.103
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L23 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 17:09:20.877
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L20 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 17:10:19.511
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 L19 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 17:12:50.085
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Logistics_1 이(가) 목적지 WIP_RE3_1 (우선순위: 31)에 도착하여 홀드 상태로 설정됨
10-12 17:17:48.588
fms

==process1 log == 
10-12 07:29:05.213
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 CHP2 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 08:57:49.128
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A04 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:04:42.967
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A04 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:12:45.572
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 CHP2 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:16:01.952
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 CHP2 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:26:21.220
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 CHP2 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:32:47.825
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:35:11.198
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A04 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:36:57.668
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A05 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:45:52.544
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:48:11.220
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A06 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:53:23.090
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A05 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 09:57:29.850
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:03:11.054
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A06 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:13:41.378
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A05 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:16:43.751
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A06 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:19:37.539
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:22:41.274
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A21 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:41:56.538
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A05 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:44:57.020
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A06 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:47:12.973
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:49:38.130
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A21 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:52:30.074
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A04 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:57:21.988
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 10:59:50.117
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A05 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:02:19.339
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A21 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:04:59.386
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A06 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:07:45.123
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:10:50.056
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A04 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:13:11.116
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A21 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:16:22.589
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A05 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:20:21.013
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A20 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:22:56.463
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A06 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:25:06.852
fms
[ZoneManager:zone_3_p0][ARRIVAL] 로봇 SEC_Process_1 이(가) 목적지 A21 (우선순위: 21)에 도착하여 홀드 상태로 설정됨
10-12 11:27:54.621
fms
