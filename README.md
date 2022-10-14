# BirthdayProblem

## This repository contains Android source code for famous problem in probability theory called "Birthday Problem" by pigeon hole principle
//       double result = 0.0;
//
//      for(int i=1; i<=count; i++) {
//
//        Map<Integer,Integer> birthMap = new HashMap<Integer,Integer>();
//        Random day = new Random();
//        day.setSeed(i);
//
//          for(int j=1; j<=size; j++) {
//
//            int ranVal =  day.nextInt(365);
//
//            if(!birthMap.containsKey(ranVal)) {
//              birthMap.put(ranVal, 1);
//            }else {
//
//                if(birthMap.get(ranVal)>=2)
//                {
//                    break;
//                }
//              birthMap.put(ranVal, birthMap.get(ranVal)+1);
//            }
//            
//          }
//
//          if(birthMap.containsValue(2)) {
//            result++;
//          }
//
//
//        }
//        System.out.println(result);
//        return result*100/count;
